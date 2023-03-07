<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
    <card-simple />
    <card-person />
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
// import HelloWorld from '@/components/HelloWorld.vue'; otra forma de importar

import CardSimple from '@/components/CardSimple'
import CardPerson from '@/components/CardPerson'

export default {
  name: 'App',
  components: {
    CardSimple,
    CardPerson
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
