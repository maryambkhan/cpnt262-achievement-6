<template>  
  <img
    :src="props.img.url"
    :alt="props.img.alt"
    class="flex justify-center"
  />
</template>

<script setup>
import { defineProps } from "vue";
const props = defineProps({
  img: {
    type: Object
  }
});
</script>