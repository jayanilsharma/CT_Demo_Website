<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <EcommercePage msg="Welcome to Your Vue.js App"/>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import EcommercePage from './views/ecommerce/Ecommerce.vue'

export default {
  name: 'App',
  components: {
    EcommercePage
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

//<head>

//</head>
