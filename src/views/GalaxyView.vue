<template>
  <div>Welcome to the galaxy</div>
  <div class="grid grid-cols-10 grid-rows-10 gap-10">
    <div v-for="quadrant in quadrants">
      <Quadrant />
    </div>
  </div>
</template>

<script setup lang="ts">
import Quadrant from '@/components/Quadrant.vue'
import { ref } from 'vue'

const quadrants = ref(new Array(100))
</script>

<style></style>
