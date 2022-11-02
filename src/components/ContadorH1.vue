<template>
  <h1 @click="funcaoIncrementa">{{ tituloValor }}</h1>
</template>

<script>

export default {
  name: 'ContadorH1',
  data(){
    return{
      tituloValor: 0,
    }
  },
  methods: {
    funcaoIncrementa(){
      this.tituloValor++
    }
  }
}
</script>
 
<style scoped>
 
</style>
