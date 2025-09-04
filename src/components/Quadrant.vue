<template>
  <div class="grid grid-cols-10 grid-rows-10">
    <div v-for="tile in tiles">
      <div>{{ tile }}</div>
    </div>
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue'

const tiles = ref(new Array<string>(100).fill('*'))
</script>

<style></style>
