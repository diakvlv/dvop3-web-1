
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
  <div class="wrapper">
    <div class="leftContainer">
      <LinkWeather name="Praha" temparature="21" />
      <LinkWeather name="Brno" temparature="21" />
      <LinkWeather name="Ostrava" temparature="21" />
      <LinkWeather name="Olomouc" temparature="21" />
    </div>
    <div class="middleContainer">
      <LinkWeather name="Praha" temparature="21" />
      <LinkWeather name="Brno" temparature="21" />
      <LinkWeather name="Ostrava" temparature="21" />
      <LinkWeather name="Olomouc" temparature="21" />
    </div>
    <div class="rightContainer">
      <LinkWeather name="Praha" temparature="21" />
      <LinkWeather name="Brno" temparature="21" />
      <LinkWeather name="Ostrava" temparature="21" />
      <LinkWeather name="Olomouc" temparature="21" />
    </div>
  </div>
</template>
<style>
.middleContainer{
  width: 49%;
}
.wrapper {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
.rightContainer { 
  background-color: lightgray;
  width: 25%;
}
.leftContainer {
  width: 25%;
  background-color: lightgray;
}
</style>