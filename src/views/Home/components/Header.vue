<script setup>
import {ref} from 'vue'
// 导航栏数组
const mainNavList = ref([
    {
        zh: "游戏资料",
        en: "DATA",
        subList: [
            {
                name: "版本介绍",
                sprite: "none"
            },
            {
                name: "游戏介绍",
                sprite: "none"
            },
            {
                name: "英雄资料",
                sprite: "none"
            },
            {
                name: "爆料站",
                sprite: "H"
            },
            {
                name: "世界观体验站",
                sprite: "N"
            },
            {
                name: "游戏壁纸",
                sprite: "O"
            }
        ]
    },
    {
        zh: "内容中心",
        en: "CONTENTS",
        subList: [
            {
                name: "版本介绍",
                sprite: "none"
            },
            {
                name: "游戏介绍",
                sprite: "none"
            },
            {
                name: "英雄资料",
                sprite: "none"
            },
            {
                name: "爆料站",
                sprite: "H"
            },
            {
                name: "世界观体验站",
                sprite: "N"
            },
            {
                name: "游戏壁纸",
                sprite: "O"
            }
        ]
    },
    {
        zh: "赛事中心",
        en: "MATCH",
        subList: [
            {
                name: "版本介绍",
                sprite: "none"
            },
            {
                name: "游戏介绍",
                sprite: "none"
            },
            {
                name: "英雄资料",
                sprite: "none"
            },
            {
                name: "爆料站",
                sprite: "H"
            },
            {
                name: "世界观体验站",
                sprite: "N"
            },
            {
                name: "游戏壁纸",
                sprite: "O"
            }
        ]
    },
    {
        zh: "百态王者",
        en: "CULTURE",
        subList: [
            {
                name: "版本介绍",
                sprite: "none"
            },
            {
                name: "游戏介绍",
                sprite: "none"
            },
            {
                name: "英雄资料",
                sprite: "none"
            },
            {
                name: "爆料站",
                sprite: "H"
            },
            {
                name: "世界观体验站",
                sprite: "N"
            },
            {
                name: "游戏壁纸",
                sprite: "O"
            }
        ]
    },
    {
        zh: "社区互动",
        en: "COMMUNITY",
        subList: [
            {
                name: "版本介绍",
                sprite: "none"
            },
            {
                name: "游戏介绍",
                sprite: "none"
            },
            {
                name: "英雄资料",
                sprite: "none"
            },
            {
                name: "爆料站",
                sprite: "H"
            },
            {
                name: "世界观体验站",
                sprite: "N"
            },
            {
                name: "游戏壁纸",
                sprite: "O"
            }
        ]
    },
    {
        zh: "玩家支持",
        en: "PLAYER",
        subList: [
            {
                name: "版本介绍",
                sprite: "none"
            },
            {
                name: "游戏介绍",
                sprite: "none"
            },
            {
                name: "英雄资料",
                sprite: "none"
            },
            {
                name: "爆料站",
                sprite: "H"
            },
            {
                name: "世界观体验站",
                sprite: "N"
            },
            {
                name: "游戏壁纸",
                sprite: "O"
            }
        ]
    },
    {
        zh: "IP新游",
        en: "NEW GAMES",
        subList: [
            {
                name: "版本介绍",
                sprite: "none"
            },
            {
                name: "游戏介绍",
                sprite: "none"
            },
            {
                name: "英雄资料",
                sprite: "none"
            },
            {
                name: "爆料站",
                sprite: "H"
            },
            {
                name: "世界观体验站",
                sprite: "N"
            },
            {
                name: "游戏壁纸",
                sprite: "O"
            }
        ]
    }
])
</script>
<template>
    <!-- 头部 -->
    <div class="header">
        <!-- 主导航 -->
        <div class="header-inner wrapper">
            <!-- 左侧 -->
            <div class="left">
                <!-- logo -->
                <div class="logo">
                    <a href="https://pvp.qq.com/" title="王者荣耀" class="logoA"></a>
                </div>
                <!-- 主菜单 -->
                <ul class="main-nav">
                    <li class="flex li-submenu" v-for="(item, index) in mainNavList" :key="index">
                        <a href="#">
                            <p class="zh">{{ item.zh }}</p>
                            <p class="en">{{ item.en }}</p>
                        </a>
                    </li>
                </ul>
            </div>
            <!-- 右侧 -->
            <div class="right">
                <!-- 欢迎登陆的图标 -->
                <div class="login_logo">
                    <a href="#">
                        <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACoAAAAqCAMAAADyHTlpAAAABGdBTUEAALGPC/xhBQAAARpQTFRF88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JY88JYAAAA88JYAMCn0QAAAF10Uk5TZBSP1dYNDujnLPuA3/zQAos0UjmnB8KcgZrNkfGwCdhthtnjysFgCFAZSuQWKYNXh9IbREw+9iRhdyPlZRNdvRwnMRrvNf3F3isBtz+eRfPha+v3O+718Gm0eB4AqcfmkwAAAUBJREFUOMvt1FWTg0AMAOCeu7u71t3dFS+FJv//b9wCnbu5YwI83VPzsBvYb2aRbHzgOXxzartTLbGhVPVAN9Z0NurrXVdaE9GkKNZcaFPBVBJ6kEyh0nSksoqYAVgEyCCqsgMdcIjIpxOYSPMs4wYkHY3RiPwSLufNbDyiqIp/Q6Iob6MqRZ9t9ImiNzZ6R9ELG72k6Dl22q1v1mp38JSiE9SgLpR3mNssC3XQ2DVBD62lBR2zRSPR8JiiR9jIrgDEwhiOAazqDTyjaI7trMQhwqYIxBU2XVH01nibCYTYGGIPzuKBLJdrkwb86A9YVCfpI1uNBkHmZAhGDSqQ9MUspwLkwGcV2StJh9bHn8J09hs+Sfo2/EXFd6ezVZB+aP/D+cQebM+odN9z6wPFvkl3ux66y95WBSr7J/NW/F/0C0EhZNPgBN3FAAAAAElFTkSuQmCC"
                            width="42" height="42">
                    </a>
                </div>
                <!-- 文字 -->
                <div class="welcom">
                    <p>欢迎登录</p>
                    <p class="afterLogin">登陆后查看游戏战绩</p>
                </div>
            </div>
        </div>
        <!-- 二级菜单 -->
        <div class="subMenu">
            <ul class="sub-nav">
                <li class="" v-for="(item, index) in mainNavList" :key="index">
                    <div v-for="(item2, index2) in item.subList" :key="index2">
                        <a href="#">
                            <!-- 雪碧图标 -->
                            <div v-if="item2.sprite === 'H'" class="H"></div>
                            <div v-else-if="item2.sprite === 'N'" class="N"></div>
                            <div v-else-if="item2.sprite === 'O'" class="O"></div>
                            <!-- 链接 -->
                            {{ item2.name }}
                        </a>
                    </div>
                </li>
            </ul>
        </div>
    </div>
</template>
<style scoped>
/* 头部导航栏 */
.header {
    width: 100%;
    height: 84px;
    background: rgba(0, 0, 0, 0.8);

    .subMenu {
        height: 0px;
        transition: all .3s ease;

        .sub-nav {
            display: none;
        }
    }
}
/* 头部导航栏 鼠标经过时出现下面半透明盒子 */
.header:hover {
    .subMenu {
        background: rgba(0, 0, 0, 0.7);
        height: 285px;
        transition: all .3s ease;
        display: flex;
        align-items: center;

        .sub-nav {
            margin-left: 320px;
            padding-top: 20px;
            width: 1120-54px;
            height: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
            padding-left: 30px;

            li {
                width: 115px;
                height: 100%;
                display: flex;
                flex-direction: column;
                align-items: center;
                a {
                    height: 30px;
                    line-height: 30px;
                    font-size: 14px;
                    color: #c9c9dd;
                    display: flex;
                    align-items: center;

                    div {
                        margin-right: 2px;
                    }
                }
                a:hover{
                    color: #f3c258;
                    text-decoration: underline;
                }
            }
        }

    }
}
/* 头部导航栏 1300px固定部分 */
.header-inner {
    height: 84px;
    display: flex;
    align-items: center;
    justify-content: space-between;

    .left {
        width: 1120px;
        height: 100%;
        display: flex;
        align-items: center;

        /* logo */
        .logo {
            width: 200px;
            height: 54px;

            .logoA {
                display: inline-block;
                background-image: url("https://game.gtimg.cn/images/yxzj/web201706/images/comm/logo.png");
                width: 100%;
                height: 100%;
            }
        }

        /* 主菜单 */
        .main-nav {
            flex: 1;
            height: 100%;
            display: flex;
            align-items: center;
            padding-left: 30px;

            li {
                width: 115px;
                height: 100%;

                a {
                    display: flex;
                    flex-direction: column;
                    justify-content: center;
                    align-items: center;
                }

                .zh {
                    font-size: 18px;
                    color: #fff;
                    margin-bottom: 5px;
                }

                .en {
                    font-size: 12px;
                    color: #858792;
                }
            }

            li:hover {
                background-image: url("https://game.gtimg.cn/images/yxzj/web201706/images/comm/index.png");
                background-position: 0 0;
            }

            li:hover .zh {
                color: #e4b653;
            }

            li:hover .en {
                color: #e4b653;
            }
        }
    }

    .right {
        width: 182px;
        height: 45px;
        display: flex;
        align-items: center;

        .login_logo {
            width: 42px;
            height: 42px;

            img {
                border: 1px solid #d9ad50;
                border-radius: 42px;
            }
        }

        .welcom {
            flex: 1;
            height: 100%;
            font-size: 16px;
            padding-left: 8px;
            color: #fff;

            .afterLogin {
                font-size: 14px;
                color: #858792;
            }
        }
    }
}

/* 雪碧图 N H O */
.H {
    width: 20px;
    height: 20px;
    background-image: url("https://game.gtimg.cn/images/yxzj/web201706/images/comm/index.png");
    background-repeat: no-repeat;
    background-position: -140px -69px;
}

.N {
    width: 21px;
    height: 21px;
    background-image: url("https://game.gtimg.cn/images/yxzj/web201706/images/comm/index.png");
    background-repeat: no-repeat;
    background-position: -163px -69px;
}

.O {
    width: 21px;
    height: 21px;
    background-image: url("https://game.gtimg.cn/images/yxzj/web201706/images/comm/index.png");
    background-repeat: no-repeat;
    background-position: -139px -7px;
}
</style>