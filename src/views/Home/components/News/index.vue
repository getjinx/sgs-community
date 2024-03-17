<script setup>
import LeftSwiper from "./components/LeftSwiper.vue"
import CenterTab from "./components/CenterTab.vue"
import DounloadPannel from "./components/DounloadPannel.vue"
</script>
<template>
    <div class="news">
        <!-- 左侧轮播图 -->
        <LeftSwiper></LeftSwiper>
        <!-- 中间Tab栏 -->
        <CenterTab></CenterTab>
        <!-- 右边下载游戏模块 -->
        <DounloadPannel></DounloadPannel>
    </div>
</template>
<style scoped>
.news {
    width: 100%;
    height: 342px;
    display: flex;
    background: rgba(0, 0, 0, 0.8);
    display: flex;
    justify-content: space-between;
}
</style>