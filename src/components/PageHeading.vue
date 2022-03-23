<template>
  <header class="flex flex-col items-center justify-center h-40 py-4">
    <h1 class="text-5xl uppercase md:text-6xl lg:text-7xl text-transparent bg-clip-text bg-gradient-to-r from-blue-400 via-emerald-600 to-pink-400 mb-8">
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