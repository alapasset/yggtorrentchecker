<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Hello Vue 3 + TypeScript + Vite + TailwindCSS" />
</template>

<style>
#app {
  @apply font-sans antialiased text-center text-gray-700 mt-16;
}

img {
  @apply m-auto mb-5;
}
</style>
