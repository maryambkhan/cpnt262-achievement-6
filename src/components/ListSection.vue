<template>
  <ul>
    <li v-for="item in shows" :key="item.id">
      {{ item.name }}
    </li>
  </ul>
</template>

<script setup>
import { ref } from "vue";
const shows = ref([
    { name:"Friends" },
    { name:"Modern Family" },
    { name:"Life in Pieces" },
    { name:"Superstore" }
]);
</script>
