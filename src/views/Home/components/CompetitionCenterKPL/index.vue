<script setup>
import CompetitionCenter from "./components/CompetitionCenter.vue"
import KPL from "./components/KPL.vue"
</script>
<template>
    <div class="CompetitionCenterKPL">
        <CompetitionCenter></CompetitionCenter>
        <KPL></KPL>
    </div>
</template>
<style scoped>
.CompetitionCenterKPL{
    margin-top: 28px;
    height: 777.8px;
    width: 100%;
    display: flex;
    justify-content: space-between;
}
</style>