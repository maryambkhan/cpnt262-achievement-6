<template>
<div class="mt-4">
<footer class="grid place-items-center text-center  bg-red-400">
  <p class="text-white text-xl py-8">{{ props.title }}</p>
</footer>
</div>
</template>

<script setup>
const props = defineProps({
  title: {
    type: String,
    default: '&copy; 2022'
  }
});
</script>