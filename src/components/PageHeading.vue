<template>
  <header class="flex flex-col items-center justify-center h-40 py-4">
    <h1 class="text-5xl uppercase md:text-6xl lg:text-7xl">
      {{ props.title }}
    </h1>
  </header>
</template>

<script setup>
const props = defineProps({
  title: {
    type: String
  }
});
</script>