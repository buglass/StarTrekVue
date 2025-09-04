<template>
  <div>Welcome to the galaxy</div>
  <div class="grid grid-cols-10 grid-rows-10">
    <div v-for="quadrant in quadrants">
      <div>{{ quadrant }}</div>
    </div>
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue'

const quadrants = ref(new Array<string>(100).fill('*'))
</script>

<style></style>
