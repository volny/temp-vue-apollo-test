<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <ApolloExample />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import ApolloExample from './components/ApolloExample.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    ApolloExample
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
