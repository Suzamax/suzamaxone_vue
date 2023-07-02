<script setup>
defineProps({
  item: {
    type: String,
    required: true
  }
})
</script>

<template>
    {{ item }}
</template>