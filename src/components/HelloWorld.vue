<script setup lang="ts">
import { ref } from 'vue'

defineProps<{ msg: string }>()

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>

  <p>See <code>README.md</code> for more information.</p>

  <p>
    <a href="https://vitejs.dev/guide/features.html" target="_blank">
      Vite Docs
    </a>
    |
    <a href="https://v3.vuejs.org/" target="_blank">Vue 3 Docs</a>
    |
    <a href="https://tailwindcss.com/docs/" target="_blank"
      >Tailwind CSS Docs</a
    >
  </p>

  <button type="button" @click="count++">count is: {{ count }}</button>
</template>

<style scoped>
a {
  @apply text-green-400;
}

code {
  @apply bg-white py-1 px-2 rounded-sm text-gray-900;
}

button {
  @apply bg-green-400 rounded p-3 mt-5 cursor-pointer;
}
</style>
