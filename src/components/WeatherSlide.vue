<script setup>
import WeatherButton from './WeatherButton.vue';

</script>

<template>
    <div class="weather">
        <WeatherButton class="weather-button"/>
        <WeatherButton class="weather-button"/>
        <WeatherButton class="weather-button"/>
        <WeatherButton class="weather-button"/>
    </div>
</template>

<style scoped>
    .weather {
        position: relative;
        display: flex;
        justify-content: center;
        gap: 11px;
    }

    .weather-button {
        display: flex;
        justify-content: center;
        align-items: center;
    }
</style>