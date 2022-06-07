<template>
  <div id="app">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <newComponent/>
    <jumbo/>
  </div>
</template>

<script>

import HelloWorld from './components/HelloWorld.vue'
import newComponent from './components/newComponent.vue'
import jumbo from './components/jumbo.vue'


export default {
  name: 'App',
  components: {
    HelloWorld,
    newComponent,
    jumbo
  
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: 60px;
}
</style>
