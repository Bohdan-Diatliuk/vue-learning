<script setup>
import WeatherButton from './WeatherButton.vue';

</script>

<template>
    <div class="weather">
        <WeatherButton class="button"/>
        <WeatherButton class="button"/>
        <WeatherButton class="button"/>
        <WeatherButton class="button"/>
    </div>
</template>

<style scoped>
    .weather {
        position: relative;
        display: flex;
        justify-content: center;
        gap: 11px;
    }

    .button {
        display: flex;
        justify-content: center;
        align-items: center;
    }
</style>