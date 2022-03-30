<template>
  <img
    alt="Vue logo"
    src="./assets/logo.png" />
  <HelloWorld msg="Welcome to Your Vue.js Ahpp" />
  <FirstPage msg="This gonna be fun" />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import FirstPage from './components/FirstPage'

export default {
  name: 'App',
  components: {
    HelloWorld,
    FirstPage
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
