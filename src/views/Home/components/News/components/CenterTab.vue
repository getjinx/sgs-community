<script setup>
import { ref } from "vue"
const tabList = ref([
    {
        title: '热门',
        hot: "【王者荣耀村运会】观赛赢好礼，iPhone15promax等你来！",
        list: [
            {
                title: '手Q鹅毛市集点券红包功能异常说明恢复公告',
                time: '03/08',
            },
            {
                title: '手Q鹅毛市集点券红包功能异常说明恢复公告',
                time: '03/08',
            },
            {
                title: '手Q鹅毛市集点券红包功能异常说明恢复公告',
                time: '03/08',
            },
            {
                title: '手Q鹅毛市集点券红包功能异常说明恢复公告',
                time: '03/08',
            },
            {
                title: '手Q鹅毛市集点券红包功能异常说明恢复公告',
                time: '03/08',
            },
            {
                title: '手Q鹅毛市集点券红包功能异常说明恢复公告',
                time: '03/08',
            },
            {
                title: '手Q鹅毛市集点券红包功能异常说明恢复公告',
                time: '03/08',
            },
        ]
    },
    {
        title: '新闻',
        hot: "鲤跃龙门一键回程——王者荣耀×携程旅行新春联动企划开启",
        list: [
            {
                title: '千载相逢一聚成龙，乘龙上王者过福运新春',
                time: '03/08',
            },
            {
                title: '千载相逢一聚成龙，乘龙上王者过福运新春',
                time: '03/08',
            },
            {
                title: '千载相逢一聚成龙，乘龙上王者过福运新春',
                time: '03/08',
            },
            {
                title: '千载相逢一聚成龙，乘龙上王者过福运新春',
                time: '03/08',
            },
            {
                title: '千载相逢一聚成龙，乘龙上王者过福运新春',
                time: '03/08',
            },
            {
                title: '千载相逢一聚成龙，乘龙上王者过福运新春',
                time: '03/08',
            },
            {
                title: '千载相逢一聚成龙，乘龙上王者过福运新春',
                time: '03/08',
            },
        ]
    },
    {
        title: '公告',
        hot: "3月8日体验服停机更新公告",
        list: [
            {
                title: '号外号外，能线下围观狼队、AG对战啦，成渝体育产业联盟杯等你来！',
                time: '03/08',
            },
            {
                title: '号外号外，能线下围观狼队、AG对战啦，成渝体育产业联盟杯等你来！',
                time: '03/08',
            },
            {
                title: '号外号外，能线下围观狼队、AG对战啦，成渝体育产业联盟杯等你来！',
                time: '03/08',
            },
            {
                title: '号外号外，能线下围观狼队、AG对战啦，成渝体育产业联盟杯等你来！',
                time: '03/08',
            },
            {
                title: '号外号外，能线下围观狼队、AG对战啦，成渝体育产业联盟杯等你来！',
                time: '03/08',
            },
            {
                title: '号外号外，能线下围观狼队、AG对战啦，成渝体育产业联盟杯等你来！',
                time: '03/08',
            },
            {
                title: '号外号外，能线下围观狼队、AG对战啦，成渝体育产业联盟杯等你来！',
                time: '03/08',
            },
        ]
    },
    {
        title: '活动',
        hot: "龙吟剑意限定皮肤返场抽奖开启公告",
        list: [
            {
                title: '妇女节快乐！福利助力共庆节日',
                time: '03/08',
            },
            {
                title: '妇女节快乐！福利助力共庆节日',
                time: '03/08',
            },
            {
                title: '妇女节快乐！福利助力共庆节日',
                time: '03/08',
            },
            {
                title: '妇女节快乐！福利助力共庆节日',
                time: '03/08',
            },
            {
                title: '妇女节快乐！福利助力共庆节日',
                time: '03/08',
            },
            {
                title: '妇女节快乐！福利助力共庆节日',
                time: '03/08',
            },
            {
                title: '妇女节快乐！福利助力共庆节日',
                time: '03/08',
            },
        ]
    },
    {
        title: '赛事',
        hot: "号外号外，能线下围观狼队、AG对战啦，成渝体育产业联盟杯等你来！",
        list: [
            {
                title: '菜狗大作战上线公告与FAQ',
                time: '03/08',
            },
            {
                title: '菜狗大作战上线公告与FAQ',
                time: '03/08',
            },
            {
                title: '菜狗大作战上线公告与FAQ',
                time: '03/08',
            },
            {
                title: '菜狗大作战上线公告与FAQ',
                time: '03/08',
            },
            {
                title: '菜狗大作战上线公告与FAQ',
                time: '03/08',
            },
            {
                title: '菜狗大作战上线公告与FAQ',
                time: '03/08',
            },
            {
                title: '菜狗大作战上线公告与FAQ',
                time: '03/08',
            },
        ]
    }
])
const activeIndex = ref(0)
const activeItem = (index) => {
    activeIndex.value = index
}
</script>
<template>
    <div class="centerTab">
        <!-- 头部导航 热门 新闻... -->
        <div class="ai">
            <span title="更多">...</span>
            <ul class="tab-hd">
                <li v-for="(item, index) in tabList" :key="index" :class="index === activeIndex ? 'active' : ''"
                    @mouseover="activeItem(index)">{{ item.title }}</li>
            </ul>
        </div>
        <!-- 中间标题 -->
        <div class="title">
            <p v-if="tabList[activeIndex].hot">
                {{ tabList[activeIndex].hot }}
            </p>
        </div>
        <!-- 新闻列表 -->
        <ul class="tab-list">
            <li v-for="(item, index) in tabList[activeIndex].list" :key="index">
                <a href="#">
                    <span class="notice">公告</span>
                    <span class="content">{{ item.title }}</span>
                </a>
                <em class="news_time">{{ item.time }}</em>
            </li>
        </ul>
    </div>
</template>
<style scoped>
.active {
    color: #f3c258 !important;
    border-bottom: 3px solid #f3c258;
}

.ai {
    position: relative;

    span {
        position: absolute;
        top: 6px;
        right: 30px;
        color: #b8b9c5;
    }
}

.centerTab {

    width: 325px;
    height: 342px;
    display: flex;
    /* background: rgba(0, 0, 0, 0.7); */
    flex-direction: column;

    .tab-hd {
        width: 100%;
        height: 45px;
        display: flex;
        border-bottom: 1px solid #000;

        li {
            width: 52px;
            height: 45px;
            line-height: 45px;
            font-size: 14px;
            text-align: center;
            color: #b8b9c5;
            padding-bottom: 3px;
        }


        .notLi:hover {
            border-bottom: none;
            color: #b8b9c5;
        }
    }

    .title {
        width: 100%;
        height: 36px;
        line-height: 36px;
        margin-top: 17px;
        text-align: center;
        padding-left: 10px;
        font-size: 18px;
        color: #333333;
        background: #414046;
        margin-bottom: 5px;

        p {
            width: 230px;
            height: 36px;
            color: #f3c258;
            overflow: hidden;
            /*文本不会换行*/
            white-space: nowrap;
            /*当文本溢出包含元素时，以省略号表示超出的文本*/
            text-overflow: ellipsis;
        }
    }

    .tab-list {
        width: 100%;
        flex: 1;
        display: flex;
        flex-direction: column;
        justify-content: space-evenly;

        li {
            width: 100%;
            height: 21px;
            display: flex;
            justify-content: space-between;
            align-items: center;

            a {
                display: inline-block;
                display: flex;
                justify-content: space-between;
                align-items: center;

                .notice {
                    width: 32px;
                    height: 16px;
                    line-height: 16px;
                    border: 1px solid #f3c258;
                    text-align: center;
                    margin-right: 5px;
                    font-size: 12px;
                    border-radius: 2px;
                    color: #f3c258;
                    display: inline-block;
                }

                .content {
                    width: 230px;
                    text-overflow: ellipsis;
                    white-space: nowrap;
                    overflow: hidden;
                    display: inline-block;
                    vertical-align: center;
                    color: #b8b9c5;
                    font-size: 14px
                }
            }

            .news_time {
                font-size: 12px;
                color: #b8b9c5;
            }
        }
    }
}
</style>