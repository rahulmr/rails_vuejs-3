<template>
  <div id="app">
    <p v-if="message">{{ message }}</p>
  </div>
</template>

<script>
export default {
  props: ['message'],
  data() {
    return {

    };
  },

}
</script>

<style scoped>
p {
  font-size: 2em;
  text-align: center;
}
</style>
