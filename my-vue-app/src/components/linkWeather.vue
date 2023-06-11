<script setup>
import { isIntegerKey } from '@vue/shared';

defineProps({
  name: String,
  temparature: Number,
  city: String,
  image1: String,
  image2: String
})


</script>
<template>
    <div class="flexbox">
     
      <p class="name">{{ name }}</p>
      <p class="temparature">{{ temparature }}</p>
       <div class="img">
      <img
      :src="temparature > 15 ? image2 : image1"
      :class="{'image-warm': temparature > 15, 'image-cold': temparature <= 15 }"/>
    </div>
                
    </div>
</template>

<style scoped>
*{
  background-color: white;
}
template{
  height: 20%;
}
.flexbox {
  display: flex;
  width: 100%;
  gap: 10px;
  
}
img {
  text-align: center;
  width: 40%;
  height: 90%;
}
.name, 
.temparature,
.img
{
  flex-basis: 50%;
  text-align: center;
  flex-grow: 1;
}
</style>