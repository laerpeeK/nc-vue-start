<template>
  <h1>Hello Vue! --version {{ version }}</h1>
</template>

<script setup>
import { ref } from 'vue'
const version = ref('3.2.45')
</script>

<style scoped>
h1 {
  color: lightskyblue;
}
</style>
