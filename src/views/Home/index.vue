<script setup>
import Header from "./components/Header.vue"
import News from "./components/News/index.vue"
import QuickEntrance from "./components/QuickEntrance.vue"
import ContentHero from "./components/ContentHero/index.vue"
import CompetitionCenterKPL from "./components/CompetitionCenterKPL/index.vue"
</script>
<template>
    <div class="index">
        <Header></Header>
        <div class="main">
            <!-- 首屏新闻资讯 -->
            <News></News>
            <!-- 快速入口 -->
            <QuickEntrance></QuickEntrance>
            <!-- 内容中心和英雄/皮肤 -->
            <ContentHero></ContentHero>
            <!-- 赛事中心和KPL赛程 -->
            <CompetitionCenterKPL></CompetitionCenterKPL>
        </div>
    </div>
</template>
<style scoped>
/* 首页背景图 */
.index {
    width: 100%;
    background-image: url("https://ossweb-img.qq.com/upload/webplat/info/yxzj/20240304/13458202714920.jpg");
    overflow: hidden;
    position: absolute;
    left: 0;
    top: 0;
    background-repeat: no-repeat;
    background-position: center top;
}

/* 主体部分 */
.main {
    width: 1200px;
    margin: 0 auto;
    margin-top: 452px;
    min-height: 600px;
}
</style>