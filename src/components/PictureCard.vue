<script setup>
import { SunIcon } from 'lucide-vue-next';

</script>

<template>
    <div class="card">
        <SunIcon  class="sun"/>
        <h3>30 градусів</h3>
        <h3>Сонячно</h3>
    </div>
</template>

<style scoped>
    .card {
        position: fixed;
        left: 26%;
        bottom: 26%;
        font-size: 30px;

        display: flex;
        flex-direction: column;
        gap: 10px;
    }

    .card h3 {
        margin: 0px;
    }

    .sun {
        width: 80px;
        height: 80px;
        margin-bottom: 10px;
    }
</style>