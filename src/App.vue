<script setup>
import Button from './components/Button.vue';
import WeatherButton from './components/WeatherButton.vue';
import Picture from './components/Picture.vue';
import PictureCard from './components/PictureCard.vue';
import PictureText from './components/PictureText.vue';
import Forecast from './components/Forecast.vue';
import WeatherSlide from './components/WeatherSlide.vue';
import FormForWeather from './components/FormForWeather.vue';

</script>

<template>
  <main class="block">
    <Forecast />
    <WeatherSlide />
    <!-- <Button>Детальніше</Button> -->
     
    <FormForWeather />
  </main>
  <Picture>
    <PictureText />
    <PictureCard />
  </Picture>
</template>

<style scoped>
  .block {
    position: absolute;
    border-radius: 20px;
    left: 48%;
    top: 20%;
    width: 500px;
    height: 400px;
    background-color: rgba(34, 40, 49, 1);
  }
</style>
