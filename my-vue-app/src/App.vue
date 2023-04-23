<script setup>
</script>

<template>
  <!--<div>
        <a href="https://vitejs.dev/" target="_blank">
                <img src="/vite.svg" class="logo" alt="Vite logo" />
              </a>
              <a href="https://vuejs.org/" target="_blank">
                <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
              </a>
            </div>-->
  <div class="wrapper">
    <div class="leftContainer">
      LEVÝ
    </div>
    <div class="middleContainer">
      PROSTŘEDNÍ
    </div>
    <div class="rightContainer">
      PRAVÝ
    </div>
  </div>
</template>
<style>
.prev {
  display: flex;
    gap: 20px;
    justify-content: space-between;
    padding: 0 20px;
}

.middleContainer {
  width: 49%;
  background-color: lightgray
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