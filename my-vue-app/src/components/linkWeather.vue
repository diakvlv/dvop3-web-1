<script setup>
import { isIntegerKey } from '@vue/shared';

defineProps({
  name: String,
  temparature: Number
})
</script>
<template>
    <div class="flexbox">
      <p class="name">{{ name }}</p>
      <p class="temparature">{{ temparature }}</p>
    </div>
</template>

<style>

.flexbox {
  background-color: lightgray;
  display: flex;
  width: 100%;
  gap: 10px;
  
}

.name,
.temparature {
  flex-basis: 50%;
  text-align: center;
  flex-grow: 1;
}
</style>