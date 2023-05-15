<script setup>
import { isIntegerKey } from '@vue/shared';

defineProps({
    day: String,
    temparature: Number,
    city: String,
    image1: String,
    image2: String
    
})


</script>
<template>
    <div class="flexboxx">
        <div class="img">
      <img
      :src="temparature > 15 ? image2 : image1"
      :class="{'image-warm': temparature > 15, 'image-cold': temparature <= 15 }"/>
    </div>
        <p class="temparature">{{ temparature }}</p>
        <p class="city">{{ city }}</p>
    </div>
</template>

<style scoped>
*{
  background-color: white;
}
img {
  width: 50px;
  height: 50px;
}
.flexboxx {
    flex-direction: column;
}
.city
{
  flex-basis: 50%;
  text-align: center;
  flex-grow: 1;
}
.temparature{
  text-align: center;
}
</style>