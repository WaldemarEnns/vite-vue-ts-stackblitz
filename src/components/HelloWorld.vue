<script setup lang="ts">
import { ref } from 'vue';

defineProps<{ msg: string }>();

const count = ref(0);
</script>

<template>
  <h1>{{ msg }}</h1>

  <div class="card">
    <button type="button" @click="count++">count is {{ count }}</button>
    <p>This is such a nice project! I just love it!</p>
  </div>

  <h3>Making some updates to check if I can push to my repo.</h3>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
