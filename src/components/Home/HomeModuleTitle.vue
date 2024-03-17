<script setup>
import { defineProps } from 'vue';
const props = defineProps({
    width: Number,
    height: Number,
    title: String
})
</script>
<template>
    <!-- 封装首页内容区域标题部分以实现多次复用的效果 -->
    <div class="home_module_title">
        <div class="left">
            <div class="spriteIcon" :style="{ backgroundPosition: `${props.width}px ${props.height}px` }"></div>
            <p>{{ title }}</p>
        </div>
        <div class="right">
            <div class="spriteAdd"></div>
            <p>更多</p>
        </div>
    </div>
</template>
<style scoped>
.home_module_title {
    width: 100%;
    height: 25.8px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 16px;

    .left {
        width: 140px;
        height: 100%;
        display: flex;
        align-items: center;

        .spriteIcon {
            width: 26px;
            height: 25.8px;
            background-image: url("https://game.gtimg.cn/images/yxzj/web201706/images/comm/index.png");
            background-repeat: no-repeat;
            /* background-position: 0 -107px; */
        }

        p {
            flex: 1;
            height: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 22px;
            font-weight: 600;
            letter-spacing: 1px;
        }
    }

    .right {
        width: 50px;
        height: 21px;
        display: flex;
        justify-content: space-between;

        .spriteAdd {
            width: 21px;
            height: 21px;
            background: url(//game.gtimg.cn/images/yxzj/web201706/images/comm/index.png) no-repeat -252px 4px;
        }

        p {
            color: "#999";
            font: 14px/1.5 "Microsoft YaHei", Tahoma, "simsun", sans-serif;
        }
    }

}
</style>