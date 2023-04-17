
<script setup>
import HelloWorld from './components/HelloWorld.vue'
import LinkWeather from './components/linkWeather.vue'
import RightHead from './components/rightHead.vue';
import PreviewTemp from './components/previewTemp.vue';
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
    </div>
    <div class="middleContainer">
      <LinkWeather name="Praha" temparature="21" />

    </div>
    <div class="rightContainer">
      <RightHead head1="<" head2="Head" head3=">" />
      <div class="prev">
        <PreviewTemp day="Tddm" temp="Tddm" city="Tddm" />
        <PreviewTemp day="Tddm" temp="Tddm" city="Tddm" />
        <PreviewTemp day="Tddm" temp="Tddm" city="Tddm" />
      </div>

      <LinkWeather name="Praha" temparature="21"
        image1="https://png.pngtree.com/png-clipart/20201029/ourmid/pngtree-circle-clipart-blue-circle-png-image_2381949.jpg"
        image2="https://www.vhv.rs/dpng/d/443-4431349_yellow-circle-png-transparent-png-download.png" />
      <LinkWeather name="Brno" temparature="13"
        image1="https://png.pngtree.com/png-clipart/20201029/ourmid/pngtree-circle-clipart-blue-circle-png-image_2381949.jpg"
        image2="https://www.vhv.rs/dpng/d/443-4431349_yellow-circle-png-transparent-png-download.png" />
      <LinkWeather name="Ostrava" temparature="18"
        image1="https://png.pngtree.com/png-clipart/20201029/ourmid/pngtree-circle-clipart-blue-circle-png-image_2381949.jpg"
        image2="https://www.vhv.rs/dpng/d/443-4431349_yellow-circle-png-transparent-png-download.png" />
      <LinkWeather name="Olomouc" temparature="21"
        image1="https://png.pngtree.com/png-clipart/20201029/ourmid/pngtree-circle-clipart-blue-circle-png-image_2381949.jpg"
        image2="https://www.vhv.rs/dpng/d/443-4431349_yellow-circle-png-transparent-png-download.png" />
      <LinkWeather name="Liberec" temparature="14"
        image1="https://png.pngtree.com/png-clipart/20201029/ourmid/pngtree-circle-clipart-blue-circle-png-image_2381949.jpg"
        image2="https://www.vhv.rs/dpng/d/443-4431349_yellow-circle-png-transparent-png-download.png" />
      <LinkWeather name="Karlovy Vary" temparature="21"
        image1="https://png.pngtree.com/png-clipart/20201029/ourmid/pngtree-circle-clipart-blue-circle-png-image_2381949.jpg"
        image2="https://www.vhv.rs/dpng/d/443-4431349_yellow-circle-png-transparent-png-download.png" />
      <LinkWeather name="J. Hradec" temparature="13"
        image1="https://png.pngtree.com/png-clipart/20201029/ourmid/pngtree-circle-clipart-blue-circle-png-image_2381949.jpg"
        image2="https://www.vhv.rs/dpng/d/443-4431349_yellow-circle-png-transparent-png-download.png" />
      <LinkWeather name="Jihlava" temparature="12"
        image1="https://png.pngtree.com/png-clipart/20201029/ourmid/pngtree-circle-clipart-blue-circle-png-image_2381949.jpg"
        image2="https://www.vhv.rs/dpng/d/443-4431349_yellow-circle-png-transparent-png-download.png" />
      <LinkWeather name="Chomutov" temparature="21"
        image1="https://png.pngtree.com/png-clipart/20201029/ourmid/pngtree-circle-clipart-blue-circle-png-image_2381949.jpg"
        image2="https://www.vhv.rs/dpng/d/443-4431349_yellow-circle-png-transparent-png-download.png" />
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

.mod {
  flex-direction: column;
}

.RightHead {
  height: 100px;
}

.middleContainer {
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