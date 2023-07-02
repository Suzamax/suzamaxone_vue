<script setup>
import { RouterLink } from 'vue-router'

defineProps({
  pageTitle: {
    type: String,
    required: true
  }
})
</script>



<template>
  <nav class="mb-5 shadow-lg">
    <div class="container mx-auto flex p-2">
      <h1 class="text-2xl mr-auto">{{ pageTitle }}</h1>

      <div class="ml-auto space-x-3 mr-3 p-1">
        <RouterLink to="/" class="p-2 rounded-sm hover:bg-slate-200 hover:text-slate-900">Home</RouterLink>
        <RouterLink to="/about" class="p-2 rounded-sm hover:bg-slate-200 hover:text-slate-900">About</RouterLink>
      </div>
    </div>
  </nav>
</template>
