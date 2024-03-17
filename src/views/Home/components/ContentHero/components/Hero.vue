<script setup>
import { ref } from "vue"
import HomeModuleTitle from "@/components/Home/HomeModuleTitle.vue"
const heroList = ref([
    {
        title: "最新英雄",
        middle: {
            img: "https://game.gtimg.cn/images/yxzj/img201606/freehero/horizontal/aoyin.jpg",
            mid_title: "新英雄：敖隐",
            time: "2024.02.06"
        },
        bottomList: [
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/freehero/vertical/563.jpg",
                name: "梅诺"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/freehero/vertical/563.jpg",
                name: "梅诺"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/freehero/vertical/563.jpg",
                name: "梅诺"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/freehero/vertical/563.jpg",
                name: "梅诺"
            },
        ]
    },
    {
        title: "最新皮肤",
        middle: {
            img: "https://game.gtimg.cn/images/yxzj/img201606/freehero/horizontal/lubanqihao_skin.jpg",
            mid_title: "新英雄：敖隐",
            time: "2024.02.06"
        },
        bottomList: [
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/freehero/vertical/bianque_skin.jpg",
                name: "梅诺"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/freehero/vertical/bianque_skin.jpg",
                name: "梅诺"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/freehero/vertical/bianque_skin.jpg",
                name: "梅诺"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/freehero/vertical/bianque_skin.jpg",
                name: "梅诺"
            },
        ]
    },
    {
        title: "周免英雄",
        middle: {
            img: "https://game.gtimg.cn/images/yxzj/img201606/freehero/horizontal/aoyin.jpg",
            mid_title: "新英雄：敖隐",
            time: "2024.02.06"
        },
        bottomList: [
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/freehero/vertical/563.jpg",
                name: "梅诺"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/freehero/vertical/563.jpg",
                name: "梅诺"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/freehero/vertical/563.jpg",
                name: "梅诺"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/freehero/vertical/563.jpg",
                name: "梅诺"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/freehero/vertical/563.jpg",
                name: "梅诺"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/freehero/vertical/563.jpg",
                name: "梅诺"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/freehero/vertical/563.jpg",
                name: "梅诺"
            },
            {
                img: "https://game.gtimg.cn/images/yxzj/img201606/freehero/vertical/563.jpg",
                name: "梅诺"
            },
        ]
    }
])

const activeIndex = ref(0)
const changeActiveIndex = (index) => {
    activeIndex.value = index
}
</script>
<template>
    <div class="hero">
        <HomeModuleTitle title="英雄/皮肤" width="0" height="-144"></HomeModuleTitle>
        <ul class="heroTab">
            <li :class="{ active: activeIndex === index }" @mouseover="changeActiveIndex(index)"
                v-for="(item, index) in heroList" :key="index">
                {{ item.title }}
            </li>
        </ul>
        <!-- 最新英雄和最新皮肤 -->
        <div class="heroContent" v-show="heroList[activeIndex] && activeIndex < 2">
            <div class="middle">
                <img :src="heroList[activeIndex].middle.img" class="heroImg" alt="">
                <p class="title">{{ heroList[activeIndex].middle.mid_title }}</p>
                <p class="time">上线时间：{{ heroList[activeIndex].middle.time }}</p>
            </div>
        </div>
        <div class="heroBottom" v-show="activeIndex < 2">
            <ul>
                <li v-for="(item, index) in heroList[activeIndex].bottomList " :key="index"
                    :class="activeIndex < 2 ? 'li01' : 'li2'">
                    <img :src="item.img" alt="">
                    <div class="imgHover">
                        <p>{{ item.name }}</p>
                    </div>
                </li>
            </ul>
        </div>
        <!-- 周免英雄 -->
        <ul class="weekHero" v-show="activeIndex == 2">
            <li v-for="(item, index) in heroList[2].bottomList" :key="index">
                <img :src="item.img" alt="">
                <div class="imgHover">
                    <p>{{ item.name }}</p>
                </div>
            </li>
        </ul>
        <p v-show="activeIndex == 2" class="timer">
            <span class="time_icon"></span>
            <span class="time_text">限免时间：2024-3-11至2024-3-17</span>
        </p>
    </div>
</template>
<style scoped>
.hero {
    height: 100%;
    width: 295px;
    display: flex;
    flex-direction: column;

    .heroTab {
        margin-bottom: 19px;
        width: 100%;
        height: 32px;
        display: flex;
        justify-content: center;
        align-items: center;

        li {
            width: 33.3333333%;
            height: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 14px;
            color: #999;
        }

        heroTab li:nth-child(2) {
            border-left: 1px solid #999;
            border-right: 1px solid #999;

        }

        .active {
            border-bottom: 3px solid #f3c258;
            color: #333;
        }
    }

    .heroContent {
        .middle {
            width: 100%;
            height: 224px;
            border: 1px solid #e5e5e5;

            p {
                padding: 0px 15px;
            }

            .title {
                padding-top: 10px;
                font-size: 18px;
                color: #333333;
                font-weight: bold;
            }

            .time {
                color: #999999;
                font-size: 12px;
            }
        }
    }

    .heroBottom {
        margin-top: 10px;
        width: 295px;
        height: 185px;

        ul {
            width: 100%;
            height: 100%;
            display: flex;
            justify-content: space-between;

            .li01 {
                position: relative;

                p {
                    display: none;
                }
            }

            .li01:hover .imgHover {
                position: absolute;
                top: 0;
                left: 0;
                background: rgba(0, 0, 0, 0.88);
                width: 68px;
                height: 173px;
            }

            .li01:hover p {
                display: block;
                overflow: hidden;
                position: absolute;
                top: 0px;
                left: 26px;
                text-align: center;
                color: #f3c258;
                font-size: 14px;
                width: 34px;
                height: 100%;
                line-height: 16px;
                padding-left: 2px;
                -ms-writing-mode: tb-lr;
                -webkit-writing-mode: vertical-r;
                writing-mode: vertical-lr;
                letter-spacing: 0.3em;
                word-break: break-all;
            }
        }
    }

    .weekHero {
        width: 100%;
        height: 370px;
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;

        li {
            width: 68px;
            height: 173px;
            position: relative;

            img {
                width: 100%;
            }

            p {
                display: none;
            }
        }

        li:hover .imgHover {
            position: absolute;
            top: 0;
            left: 0;
            background: rgba(0, 0, 0, 0.88);
            width: 68px;
            height: 173px;
        }

        li:hover p {
            display: block;
            overflow: hidden;
            position: absolute;
            top: 0px;
            left: 26px;
            text-align: center;
            color: #f3c258;
            font-size: 14px;
            width: 34px;
            height: 100%;
            line-height: 16px;
            padding-left: 2px;
            -ms-writing-mode: tb-lr;
            -webkit-writing-mode: vertical-r;
            writing-mode: vertical-lr;
            letter-spacing: 0.3em;
            word-break: break-all;
        }
    }

    .timer {
        width: 100%;
        height: 18px;
        display: flex;
        justify-content: flex-end;
        align-items: center;
        .time_icon {
            background: url(//game.gtimg.cn/images/yxzj/web201706/images/comm/index.png) no-repeat;
            display: inline-block;
            width: 14px;
            height: 14px;
            background-position: -256px -43px;
            margin-right: 10px;
            vertical-align: middle;
        }

        .time_text {
            color: #999999;
            font-size: 12px;
            text-align: right;
        }
    }
}
</style>