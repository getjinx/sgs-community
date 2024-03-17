<script setup>
import { ref } from 'vue'
const list = ref([
    {
        time: "8-31 19:00",
        VSList: [
            {
                name: "佛山DRG",
                img: "https://smobatv-pic.tga.qq.com/203f77f44f24f446f073c7b11fb56f99.png"
            },
            {
                name: "佛山DRG",
                img: "https://smobatv-pic.tga.qq.com/203f77f44f24f446f073c7b11fb56f99.png"
            },
        ]
    },
    {
        time: "8-31 19:00",
        VSList: [
            {
                name: "佛山DRG",
                img: "https://smobatv-pic.tga.qq.com/203f77f44f24f446f073c7b11fb56f99.png"
            },
            {
                name: "佛山DRG",
                img: "https://smobatv-pic.tga.qq.com/203f77f44f24f446f073c7b11fb56f99.png"
            },
        ]
    },
    {
        time: "8-31 19:00",
        VSList: [
            {
                name: "佛山DRG",
                img: "https://smobatv-pic.tga.qq.com/203f77f44f24f446f073c7b11fb56f99.png"
            },
            {
                name: "佛山DRG",
                img: "https://smobatv-pic.tga.qq.com/203f77f44f24f446f073c7b11fb56f99.png"
            },
        ]
    },
    {
        time: "8-31 19:00",
        VSList: [
            {
                name: "佛山DRG",
                img: "https://smobatv-pic.tga.qq.com/203f77f44f24f446f073c7b11fb56f99.png"
            },
            {
                name: "佛山DRG",
                img: "https://smobatv-pic.tga.qq.com/203f77f44f24f446f073c7b11fb56f99.png"
            },
        ]
    },
    {
        time: "8-31 19:00",
        VSList: [
            {
                name: "佛山DRG",
                img: "https://smobatv-pic.tga.qq.com/203f77f44f24f446f073c7b11fb56f99.png"
            },
            {
                name: "佛山DRG",
                img: "https://smobatv-pic.tga.qq.com/203f77f44f24f446f073c7b11fb56f99.png"
            },
        ]
    },
])
import HomeModuleTitle from "@/components/Home/HomeModuleTitle.vue"
</script>
<template>
    <div class="competition_center">
        <!-- 标题 -->
        <HomeModuleTitle title="KPL赛程" width="-157" height="-106"></HomeModuleTitle>
        <!-- 购票定位 -->
        <div class="buy_ticket">
            <span></span>
            <p>购票</p>
        </div>
        <!-- 时间 战队 战队 -->
        <div class="KPL_title">
            <span class="col1">时间</span>
            <span class="col1">战队</span>
            <span class="col2"></span>
            <span class="col1">战队</span>
        </div>
        <!-- VS模块 -->
        <div class="KPL_content">
            <div v-for="(item, index) in list" :key="index" class="VSDiv">
                <span class="time">{{ item.time }}</span>
                <div class="img">
                    <img :src="item.VSList[0].img" alt="">
                    <p>{{ item.VSList[0].name }}</p>
                </div>
                <span class="vs">VS</span>
                <div class="img">
                    <img :src="item.VSList[0].img" alt="">
                    <p>{{ item.VSList[0].name }}</p>
                </div>
            </div>
        </div>
        <!-- 最后的图片 -->
        <img class="lastImg" src="//game.gtimg.cn/images/yxzj/web201706/images/index/match.jpg">
    </div>
</template>
<style scoped>
.competition_center {
    position: relative;
    height: 100%;
    width: 295px;
    display: flex;
    flex-direction: column;

    .buy_ticket {
        position: absolute;
        top: 0;
        right: 68px;
        padding-left: 22px;
        background: url(//game.gtimg.cn/images/yxzj/web201706/images/comm/index.png) no-repeat -243px -85px;
        color: #323235;
        width: 70px;
        height: 22px;
        border: 1px solid #f3c258;
        border-radius: 3px;
        box-sizing: border-box;
        text-indent: 10px;
        line-height: 19px;
    }

    .KPL_title {
        width: 100%;
        height: 32px;
        background-color: #f5f5f5;
        display: flex;
        align-items: center;

        .col1 {
            width: 83px;
            margin-right: 0;
        }

        span {
            display: block;
            float: left;
            font-size: 14px;
            color: #999;
            text-align: center;
        }

        .col2 {
            width: 43px;
            height: 29px;
            margin-right: 0;
            background: #f5f5f5;
        }
    }

    .KPL_content {
        .VSDiv {
            width: 100%;
            height: 67px;
            border-bottom: 1px solid #e5e5e5;
            display: flex;
            align-items: center;

            .time {
                width: 80px;
                color: #333333;
                font-size: 12px;
            }

            .img {
                width: 79px;
                height: 67px;
                color: #333333;
                font-size: 14px;
                text-align: center;
                display: flex;
                flex-direction: column;

                img {
                    display: block;
                    width: 25px;
                    height: 25px;
                    margin: 10px auto 0 auto;
                    border-radius: 50%;
                }

                p {
                    display: inline-block;
                    font-size: 12px;
                    line-height: 24px;
                    vertical-align: top;
                    white-space: nowrap;
                }
            }

            .vs {
                font-size: 14px;
                width: 43px;
                color: #f3c258;
                text-align: center;
                vertical-align: top;
            }
        }
    }

    .lastImg {
        margin-top: 21px;
    }
}
</style>