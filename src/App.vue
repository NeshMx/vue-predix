<template>
  <div id="app">
    <img src="./assets/logo.png">
    <px-spinner></px-spinner>
    <router-view/>
  </div>
</template>

<script>
import '../bower_components/px-spinner/px-spinner.html'
export default {
  name: 'App'
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

px-spinner {
  --px-spinner-fill-color: blue;
  --px-spinner-background-color: black;
}
</style>
