
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
          <a href=""><img src="https://cdn-icons-png.flaticon.com/512/1167/1167092.png" alt=""></a> 
        </div>
        <div class="lupa">
          <a href=""><img src="https://cdn-icons-png.flaticon.com/512/40/40031.png" alt=""></a>  
        </div>
      </div>
      <div class="middle">
        <div class="lev">
         <div class="blank">
          <div class="text-left">
            Gotham
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
            Monday8.00AM
          </div>
          <div class="text-right2">
           text
            </div>
          </div>
        </div>
     
        <div class="obr">
          <img
            src="https://play-lh.googleusercontent.com/29fAV6TZJnKEmx-aeCM3ehOIbfv30ZB6E8lgycS2sDgzt_TKavB5TsCun4B7YhLN3Q">
        </div>
      </div>
    </div>
    <div class="rightContainer">
      <div class="right">
      <RightHead head1="<" head2="Head" head3=">" />
      <div class="prev">
        <PreviewTemp temparature="17" city="Prag"
          image1="https://upload.wikimedia.org/wikipedia/commons/thumb/d/de/Eo_circle_light-blue_blank.svg/2048px-Eo_circle_light-blue_blank.svg.png"
          image2="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fb/Yellow_icon.svg/2048px-Yellow_icon.svg.png" />
        <PreviewTemp temparature="14" city="Prag"
          image1="https://upload.wikimedia.org/wikipedia/commons/thumb/d/de/Eo_circle_light-blue_blank.svg/2048px-Eo_circle_light-blue_blank.svg.png"
          image2="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fb/Yellow_icon.svg/2048px-Yellow_icon.svg.png" />
        <PreviewTemp temparature="13" city="Prag"
          image1="https://upload.wikimedia.org/wikipedia/commons/thumb/d/de/Eo_circle_light-blue_blank.svg/2048px-Eo_circle_light-blue_blank.svg.png"
          image2="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fb/Yellow_icon.svg/2048px-Yellow_icon.svg.png" />
        <PreviewTemp temparature="13" city="Prag"
          image1="https://upload.wikimedia.org/wikipedia/commons/thumb/d/de/Eo_circle_light-blue_blank.svg/2048px-Eo_circle_light-blue_blank.svg.png"
          image2="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fb/Yellow_icon.svg/2048px-Yellow_icon.svg.png" />
      </div>

      <LinkWeather name="Praha" temparature="21"
        image1="https://upload.wikimedia.org/wikipedia/commons/thumb/d/de/Eo_circle_light-blue_blank.svg/2048px-Eo_circle_light-blue_blank.svg.png"
        image2="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fb/Yellow_icon.svg/2048px-Yellow_icon.svg.png" />
      <LinkWeather name="Brno" temparature="13"
        image1="https://upload.wikimedia.org/wikipedia/commons/thumb/d/de/Eo_circle_light-blue_blank.svg/2048px-Eo_circle_light-blue_blank.svg.png"
        image2="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fb/Yellow_icon.svg/2048px-Yellow_icon.svg.png" />
      <LinkWeather name="Ostrava" temparature="18"
        image1="https://upload.wikimedia.org/wikipedia/commons/thumb/d/de/Eo_circle_light-blue_blank.svg/2048px-Eo_circle_light-blue_blank.svg.png"
        image2="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fb/Yellow_icon.svg/2048px-Yellow_icon.svg.png" />
      <LinkWeather name="Olomouc" temparature="21"
        image1="https://upload.wikimedia.org/wikipedia/commons/thumb/d/de/Eo_circle_light-blue_blank.svg/2048px-Eo_circle_light-blue_blank.svg.png"
        image2="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fb/Yellow_icon.svg/2048px-Yellow_icon.svg.png" />
      <LinkWeather name="Liberec" temparature="14"
        image1="https://upload.wikimedia.org/wikipedia/commons/thumb/d/de/Eo_circle_light-blue_blank.svg/2048px-Eo_circle_light-blue_blank.svg.png"
        image2="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fb/Yellow_icon.svg/2048px-Yellow_icon.svg.png" />
      <LinkWeather name="Karlovy Vary" temparature="21"
        image1="https://upload.wikimedia.org/wikipedia/commons/thumb/d/de/Eo_circle_light-blue_blank.svg/2048px-Eo_circle_light-blue_blank.svg.png"
        image2="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fb/Yellow_icon.svg/2048px-Yellow_icon.svg.png" />
      <LinkWeather name="J. Hradec" temparature="13"
        image1="https://upload.wikimedia.org/wikipedia/commons/thumb/d/de/Eo_circle_light-blue_blank.svg/2048px-Eo_circle_light-blue_blank.svg.png"
        image2="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fb/Yellow_icon.svg/2048px-Yellow_icon.svg.png" />
      <LinkWeather name="Jihlava" temparature="12"
        image1="https://upload.wikimedia.org/wikipedia/commons/thumb/d/de/Eo_circle_light-blue_blank.svg/2048px-Eo_circle_light-blue_blank.svg.png"
        image2="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fb/Yellow_icon.svg/2048px-Yellow_icon.svg.png" />
      <LinkWeather name="Chomutov" temparature="21"
        image1="https://upload.wikimedia.org/wikipedia/commons/thumb/d/de/Eo_circle_light-blue_blank.svg/2048px-Eo_circle_light-blue_blank.svg.png"
        image2="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fb/Yellow_icon.svg/2048px-Yellow_icon.svg.png" />
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
  padding-top: 10px;
  border-radius: 25px;
  display: flex;
}
.text-middle{
  background-color: #303c54;
  text-align: center;
  padding-left: 10px;
}
.tempBig {
  background-color: #303c54;
  padding-top: 40%;
  width: 120px;
  text-align: center;
  font-size: 80px;
  padding-left: 10px;
}
.lupa img{
  width: 30px;
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