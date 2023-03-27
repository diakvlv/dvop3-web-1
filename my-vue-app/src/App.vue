
<script setup>
import HelloWorld from './components/HelloWorld.vue'
import LinkWeather from './components/linkWeather.vue';
</script>

<template>
  <!--<div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>-->
  <LinkWeather name="Praha" temparature="21"/>
  <LinkWeather name="Brno" temparature="21"/>
  <LinkWeather name="Ostrava" temparature="21"/>
  <LinkWeather name="Olomouc" temparature="21"/>
</template>
<style>  
</style>