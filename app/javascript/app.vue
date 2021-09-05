<template>
  <div id="app">
    <p v-if="message">{{ message }}</p>
    <p v-else>fsdfdsfa</p>
  </div>
</template>

<script>
export default {
  props: ['message']
}
</script>

<style scoped>
p {
  font-size: 2em;
  text-align: center;
}
</style>
