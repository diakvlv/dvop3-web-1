<script setup>
import { isIntegerKey } from '@vue/shared';

defineProps({
 name: String,
 temparature: Number
})
</script>
<template>
    <div class = "flexbox">
    <p class = "name">{{name}}</p>
    <p class = "temparature">{{temparature}}</p>
</div>

</template>

<style>
 
.flexbox {
background-color: lightsalmon;
  display: flex;
  max-width: 30%;
  margin-left: auto;
  margin-top: 20px;
  margin-right: 20px;

}

.name, .temparature {
  flex-basis: 50%;
  text-align: center;
  flex-grow: 1;
}


</style>