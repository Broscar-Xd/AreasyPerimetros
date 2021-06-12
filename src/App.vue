<template>
  <div id="app">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <Cabecera></Cabecera>
    <Triangulo></Triangulo>
    <br><br>
    <Cuadrado></Cuadrado>
    <br><br>
    <Rectangulo></Rectangulo>
    <br><br>
    <Circulo></Circulo>
  </div>
</template>

<script>
import Cabecera from './components/Cabecera.vue'
import Triangulo from './components/Triangulo.vue'
import Cuadrado from './components/Cuadrado.vue'
import Rectangulo from './components/Rectangulo.vue'
import Circulo from './components/Circulo.vue'

export default {
  name: 'App',
  components: {
    Cabecera,
    Triangulo,
    Cuadrado,
    Rectangulo,
    Circulo
  }
}
</script>


