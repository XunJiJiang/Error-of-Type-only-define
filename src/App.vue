<script setup lang="ts">
import type { Props, Emits } from '@/types.d.ts';

defineProps<Props>();
defineEmits<Emits>();
</script>

<template>
  <div class="app">
    <h1>Welcome to Vue 3 + Vite</h1>
    <p>Click on the Vite and Vue logos to learn more</p>
    <div class="logo-container">
      <img src="./assets/logo.svg" alt="Vue logo" class="logo vue" />
      <img src="./assets/vite.svg" alt="Vite logo" class="logo vite" />
    </div>
  </div>
</template>
