<script setup>
import Button from './components/Button.vue';
import WeatherButton from './components/WeatherButton.vue';
import Picture from './components/Picture.vue';

</script>

<template>
  <main class="block">
  </main>
  <Picture>AAA</Picture>
</template>

<style scoped>
  .block {
    position: absolute;
    border-radius: 20px;
    left: 35%;
    top: 20%;
    width: 700px;
    height: 400px;
    background-color: rgba(34, 40, 49, 1);
  }
</style>
