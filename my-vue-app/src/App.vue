
<script setup>
import LinkWeather from './components/linkWeather.vue';
import RightHead from './components/rightHead.vue';
import PreviewTemp from './components/previewTemp.vue';
import MiddleInf from './components/middleInf.vue';
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
      <div class="search">
         <div class="searchBar">
          Willkomen
         </div>
         <div class="lupa">
          <a href=""><img src="https://e7.pngegg.com/pngimages/160/268/png-clipart-magnifying-glass-icon-objects-magnifying-glasses-thumbnail.png" alt=""></a> 
        </div>
        <div class="lupa">
          <a href=""><img src="https://e7.pngegg.com/pngimages/808/500/png-clipart-computer-icons-gear-wheel-art-science-technology-engineering-and-mathematics-thumbnail.png" alt=""></a>  
        </div>
      </div>
      <div class="middle">
        <div class="lev">
         <div class="blank">
          <div class="text-left">
            TEXT003
          </div>
          <div class="text-left1">
           text
            </div>
          </div>
          <div class="blank">
          <div class="tempBig">
            14
          </div>
          <div class="text-middle">
           text
            </div>
        </div>
          <div class="blank">
          <div class="text-right">
            TEXT003
          </div>
          <div class="text-right2">
           text
            </div>
          </div>
        </div>
     
        <div class="obr">
          <img
            src="https://www.floorwood.cz/galerie/1_264533/parkety-21x70x500-rustikal-iii-kourova-bila-bez-bele-original.jpg">
        </div>
      </div>
    </div>
    <div class="rightContainer">
      <div class="right">
      <RightHead head1="<" head2="Head" head3=">" />
      <div class="prev">
        <PreviewTemp temparature="17" city="Prag"
          image1="https://png.pngtree.com/png-clipart/20201029/ourmid/pngtree-circle-clipart-blue-circle-png-image_2381949.jpg"
          image2="https://www.vhv.rs/dpng/d/443-4431349_yellow-circle-png-transparent-png-download.png" />
        <PreviewTemp temparature="14" city="Prag"
          image1="https://png.pngtree.com/png-clipart/20201029/ourmid/pngtree-circle-clipart-blue-circle-png-image_2381949.jpg"
          image2="https://www.vhv.rs/dpng/d/443-4431349_yellow-circle-png-transparent-png-download.png" />
        <PreviewTemp temparature="13" city="Prag"
          image1="https://png.pngtree.com/png-clipart/20201029/ourmid/pngtree-circle-clipart-blue-circle-png-image_2381949.jpg"
          image2="https://www.vhv.rs/dpng/d/443-4431349_yellow-circle-png-transparent-png-download.png" />
        <PreviewTemp temparature="13" city="Prag"
          image1="https://png.pngtree.com/png-clipart/20201029/ourmid/pngtree-circle-clipart-blue-circle-png-image_2381949.jpg"
          image2="https://www.vhv.rs/dpng/d/443-4431349_yellow-circle-png-transparent-png-download.png" />
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
  </div>
</template>
<style>
.right{
  background-color: white;
}
*{
  background-color: lightgray;
}
.lupa  {
  background-color: aqua;
}
.middle img{
  border-radius: 20px;
}
.lupa{
  margin: 15px;
}
.blank{
  background-color:  #303c54;
}
.searchBar{
 align-items: center;
  margin: 10px;
  background-color: white;
  height: 30px;
  padding-top: 0.5%;
  border-radius: 20px;
  padding-left: 40px;
  width: 80%;
}
.search{
 height: 60px;
  margin: 40px;
  background-color: gainsboro;
  padding-top: 10px;
  border-radius: 25px;
  display: flex;
}
.text-middle{
  background-color: #303c54;
  text-align: center;
}
.tempBig {
  background-color: #303c54;
  padding-top: 40%;
  width: 120px;
  text-align: center;
  font-size: 80px;
}
.lupa img{
  width: 30px;
  background-color: yellowgreen;
}
.lev {
  background-color: #303c54;
  width: 50%;
  padding: 20px;
  flex-direction: row;
  display: flex;
}

.text-left {
  background-color: #303c54;
  margin-left: auto;
}
.text-right2{
  padding-top: 280px;
  background-color: #303c54;
  text-align: center;
  margin-left: auto;
}
.text-left1{
  background-color: #303c54;
  padding-top: 280px;
  text-align: center;
  margin-left: auto;
}
.text-right {
  background-color: #303c54;
 margin-left: auto;
}

.middle {
  display: flex;
  padding: 50px;
  margin: 40px;
  width: 75%;
  height: 340px;
  background-color: #303c54;
  border-radius: 20px;
  color:white;
}

.obr {
  width: 65%;
  height: 350px;
  border-radius: 40px;
}

.obr img {
  object-fit: cover;
  width: 100%;
  height: 100%;
}

.prev {
  display: flex;
  gap: 20px;
  justify-content: space-between;
  padding: 0 20px;
  background-color: white;
}

.mod {
  flex-direction: column;
}

.RightHead {
  height: 100px;
}

.middleContainer {
  width: 59%;
  background-color: white;
}

.wrapper {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}

.rightContainer {
  background-color: white;
  width: 25%;
}

.leftContainer {
  width: 15%;
  background-color: white;
}
</style>