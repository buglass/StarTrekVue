<template>
  <div>Welcome to the galaxy</div>
  <div v-for="quadrant in quadrants">
    <div>Quadrant {{ quadrant }}</div>
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue'

const quadrants = ref([1, 2, 3, 4, 5, 6, 7, 8, 9, 10])
</script>

<style></style>
