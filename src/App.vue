<template>
  <div id="app">
  <productData /> 
  <hr>
  <siteMap /> 
  </div>
</template>

<script>
import productData from './components/productData.vue'
import siteMap from './components/siteMap.vue';

export default {
  name: 'App',
  components: {
   productData,
   siteMap
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
