<script setup></script>
<template>
    <div class="downloadPannel">
        <!-- 下载游戏 -->
        <div href="#" class="downloadGame">
            <span class="download-ani" style="display: inline;"></span>
        </div>
        <!-- 对局环境 -->
        <div href="#" class="environment"></div>
        <!-- 体验专区 -->
        <div href="#" class="experience"></div>
    </div>
</template>
<style scoped>
/* 下载游戏的动画 */
@keyframes lightmove {
    0% {
        left: -150px;
        top: -120px;
    }

    100% {
        left: 150px;
        top: 120px;
    }
}

.downloadPannel {
    width: 236px;
    height: 342px;

    .downloadGame {
        position: relative;
        width: 236px;
        height: 128px;
        /* background-color: red; */
        background-image: url("https://game.gtimg.cn/images/yxzj/web201706/images/comm/index.png");
        background-repeat: no-repeat;
        background-position: 0 -219px;
        overflow: hidden;

        .download-ani {
            position: absolute;
            top: 0;
            left: 0;
            width: 300px;
            height: 50px;
            background-color: rgba(255, 255, 255, 0.8);
            transform: rotate(-45deg);
            filter: blur(32px);
            animation: lightmove 1.6s ease-in infinite;
            -webkit-animation: lightmove 1.6s ease-in infinite;
            /* Safari and Chrome */
        }
    }

    .environment {
        width: 236px;
        height: 106px;
        background-image: url("https://game.gtimg.cn/images/yxzj/web201706/images/comm/index.png");
        background-repeat: no-repeat;
        background-position: 0 -349px;
    }

    .experience {
        width: 236px;
        height: 108px;
        background-image: url("https://game.gtimg.cn/images/yxzj/web201706/images/comm/index.png");
        background-repeat: no-repeat;
        background-position: 0 -460px;
    }
}
</style>