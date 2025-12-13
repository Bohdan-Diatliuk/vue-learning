<script setup>
import { MapPin } from 'lucide-vue-next';

</script>

<template>
    <div class="text">
        <h2 class="text-day">Субота</h2>
        <h2 class="text-date">13 грудня 2025</h2>
        <h3 class="text-city">
            <MapPin class="text-map"/>
            Вінниця
        </h3>
    </div>
</template>

<style scoped>
    .text {
        position: fixed;
        left: 26%;
        top: 18%;

        display: flex;
        flex-direction: column;
        gap: 10px;
    }

    .text h2, .text h3 {
        margin: 0px;
    }

    .text-day {
        font-weight: 700;
        font-size: 36px;
    }

    .text-date {
        font-weight: 500;
        font-size: 20px;
    }

    .text-city {
        font-weight: 400;
        font-size: 20px;
    }

    .text-map {
        width: 30px;
        height: 20px;
    }
</style>