<template>
  <FirstCalculator />
</template>

<script>

import FirstCalculator from './components/Calculator/index.vue'

export default {
  name: 'App',
  components: {
    FirstCalculator,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
