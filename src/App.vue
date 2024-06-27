<template>
  <div id="app">
    <h1>Registro de tarjeta de crédito</h1>
    <TarjetaFormulario/>
  </div>
</template>

<script>
import TarjetaFormulario  from "./components/TarjetaFormulario.vue"
export default {
  name: 'App',
  components: {
    TarjetaFormulario
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