<script setup>
import { MapPin } from 'lucide-vue-next';

</script>

<template>
    <div class="text">
        <h2>Субота</h2>
        <h2>13 грудня 2025</h2>
        <h3>
            <MapPin class="map"/>
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
        color: white;
    }

    .map {
        width: 20px;
        height: 16px;
    }
</style>