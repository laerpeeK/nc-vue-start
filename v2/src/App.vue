<template>
  <div>
    <h1>Hello Vue! --version:{{ version }}</h1>
  </div>
</template>

<script>
export default {
  data() {
    return {
      version: '2.6.14',
    }
  },
}
</script>

<style scoped>
h1 {
  color: lightseagreen;
}
</style>
