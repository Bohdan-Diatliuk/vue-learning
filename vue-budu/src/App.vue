<script setup lang="ts">
  import budus from './data/budus';
  import './styles/App.scss'
</script>

<template>
  <div class="budus">
    <h1 class="budus__title">Hello, Vue</h1>

    <h2 class="budus__title">budus {{ budus.length }}</h2>

    <div class="budus__list" v-for="budu in budus" :key="budu.id">
      <span class="budus__title">{{ budu.title }}</span>
    </div>
  </div>
</template>

<style scoped></style>
