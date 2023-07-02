<script setup>
import { RouterView } from 'vue-router'
import item from './components/item.vue';
import MainHeader from './components/MainHeader.vue';
</script>

<template>
  <header>
    <div class="wrapper">
      <MainHeader class="bg-slate-500 text-white" page-title="Carlos Cañellas" />
    </div>
  </header>
  <RouterView />
  <item item="kubernetes" />
</template>

<style>

</style>
