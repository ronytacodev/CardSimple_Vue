<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
    <card-simple />
    <card-person />
    <card-person-sass />
    <card-portada />
    <card-portada-rediseñado />
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
// import HelloWorld from '@/components/HelloWorld.vue'; otra forma de importar

import CardSimple from '@/components/CardSimple'
import CardPerson from '@/components/CardPerson'
import CardPersonSass from '@/components/CardPersonSass'
import CardPortada from '@/components/CardPortada'
import CardPortadaRediseñado from '@/components/CardPortadaRediseñado'

export default {
  name: 'App',
  components: {
    CardSimple,
    CardPerson,
    CardPersonSass,
    CardPortada,
    CardPortadaRediseñado
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
