<script setup>
import { isIntegerKey } from '@vue/shared';

defineProps({
    img: Image
})


</script>
<template>
    <div class="flexboxx">
        <div class="immg">
      <img
      src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRTgw_L8XqGGFtpKgJrO-n6OMvdoebpXcxhqw&usqp=CAU"/>
        </div>
</div>
</template>

<style scoped>
img{
   width: 150%;
   height: 150%;
}
.flexboxx {
    flex-direction: column;
}
</style>