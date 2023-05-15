<script setup>
import { isIntegerKey } from '@vue/shared';

defineProps({
  head1: String,
  head2: String,
  head3: String,

})
</script>
<template>
    <div class="flexbox">
        <p class="headL">{{ head1 }}</p>
        <p class="headM">{{ head2 }}</p>
        <p class="headR">{{ head3 }}</p>
    </div>
</template>

<style>

.flexbox {
  display: flex;
  width: 100%;
  gap: 10px;
  background-color: white;
}
.headL
{
  height: 50px;
  flex-basis: 20%;
  text-align: right;
  flex-grow: 1;
  padding-top: 7%;
  background-color: white;
}
.headM
{
  flex-basis: 20%;
  text-align: center;
  flex-grow: 1;
  padding-top: 7%;
  background-color: white;
}
.headR
{
  flex-basis: 20%;
  text-align: left;
  flex-grow: 1;
  padding-top: 7%;
  background-color: white;
}
</style>