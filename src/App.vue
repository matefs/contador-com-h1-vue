<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <ContadorH1 />
</template>

<script>
import ContadorH1 from './components/ContadorH1.vue'

export default {
  name: 'App',
  components: {
    ContadorH1
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
