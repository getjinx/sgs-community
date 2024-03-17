<script setup>
import { ref, onMounted, watch, onUnmounted } from 'vue'
const optionList = ref([
    {
        value: '高校联赛开赛',
        img: "https://ossweb-img.qq.com/upload/adw/image/194/20240302/ac3f5af1592ef47669c4a7e78c39ca0e.jpeg"
    },
    {
        value: 'K甲回顾',
        img: "https://ossweb-img.qq.com/upload/adw/image/194/20240309/21d111e9df8e18113f9071eb49c98334.jpeg"
    },
    {
        value: '云梦区域站上线',
        img: "https://ossweb-img.qq.com/upload/adw/image/194/20240104/a7e344498c8e5e04fcbbd366e13c5209.jpeg"
    },
    {
        value: '王者萌萌假日',
        img: "	https://ossweb-img.qq.com/upload/adw/image/194/20230922/eb5486e2dfc48f5c593c5b04bd52bd3f.jpeg"
    },
])

const activeIndex = ref(0)
var timer = null
// 轮播图切换高亮和自动播放
const autoPlaySwiper = () => {
    clearInterval(timer)
    timer = setInterval(() => {
        activeIndex.value++
        if (activeIndex.value === optionList.value.length) {
            activeIndex.value = 0
        }
    }, 3000)
}

// 通过watch监听数据改变后是否自动播放
watch(activeIndex, (newValue, oldValue) => {
    if (newValue.value) {
        autoPlaySwiper();
    }
})

// 鼠标进入暂停定时器，离开开启定时器，给父元素绑定 @mouseenter="stop()" @mouseleave="start()"事件
const stop = () => {
    if (timer) clearInterval(timer);
};
const start = () => {
    if (optionList.value.length) {
        autoPlaySwiper();
    }
};

// 一进页面就开始轮播
onMounted(() => {
    autoPlaySwiper()
})

// 组件卸载时，清除定时器
onUnmounted(() => {
    clearInterval(timer);
})

</script>
<template>
    <!-- 轮播图 -->
    <div class="leftSwiper" @mouseenter="stop()" @mouseleave="start()">
        <!-- 上方图片 -->
        <div class="pic">
            <img :src="optionList[activeIndex].img" alt="">
        </div>
        <ul class="option">
            <!-- 下方选项按钮 -->
            <li @mouseover="activeIndex = index" :class="activeIndex === index ? 'active' : ''" class="flex"
                v-for="(item, index) in optionList" :key="index">{{
        item.value }}</li>
        </ul>
    </div>
</template>
<style scoped>
.leftSwiper {
    width: 605px;
    height: 100%;

    .pic {
        width: 100%;
        height: 298px;

        img {
            width: 100%;
            height: 100%;
        }
    }

    .option {
        width: 100%;
        height: 44px;
        display: flex;
        background-color: #000000;

        li {
            width: 120.8px;
            height: 100%;
            color: #b1b2be;
            font: 14px/1.5 "Microsoft YaHei", Tahoma, "simsun", sans-serif;
        }

        .active {
            background: rgba(255, 255, 255, 0.15);
            color: #f3c258;
        }
    }
}
</style>