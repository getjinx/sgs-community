<script setup>
import ContentCenter from "./components/ContentCenter.vue"
import Hero from "./components/Hero.vue"
</script>
<template>
    <div class="content-hero">
        <ContentCenter></ContentCenter>
        <Hero></Hero>
    </div>
</template>
<style scoped>
.content-hero{
    margin-top: 28px;
    height: 549px;
    width: 100%;
    display: flex;
    justify-content: space-between;
}
</style>