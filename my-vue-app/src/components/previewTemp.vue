<script setup>
import { isIntegerKey } from '@vue/shared';

defineProps({
    day: String,
    temp: Number,
    city: String
})


</script>
<template>
    <div class="flexboxx">
        <p class="day">{{ day }}</p>
        <p class="temp">{{ temp }}</p>
        <p class="day">{{ city }}</p>
    </div>
</template>

<style>
.flexboxx {
    flex-direction: column;
}
</style>