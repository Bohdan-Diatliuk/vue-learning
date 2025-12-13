<script setup>
import { SunMedium } from 'lucide-vue-next';

</script>

<template>
    <div class="card">
        <SunMedium class="card-sun"/>
        <h3 class="card-degree">25°</h3>
        <h3 class="card-day">day</h3>
    </div>
</template>

<style scoped>
    .card {
        display: flex;
        flex-direction: column;
        color: white;
        background: rgba(39, 46, 55, 1);
        border-radius: 8px;
        width: 90px;
        height: 120px;
        
        transition: transform 0.3s, background 0.3s;
    }

    .card:hover {
        background: rgba(58, 67, 79, 1);
        transform: translateY(-6px);
    }

    .card-sun {
        width: 30px;
        height: 30px;
        margin-bottom: 10px;
    }

    .card h3 {
        font-size: 15px;
        margin: 5px;
    }

    .card-degree {
        font-weight: 400;
    }

</style>