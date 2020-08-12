<template>
  <div id="app">
    <h2>master的h2</h2>
    <h3>master的h3</h3>
    <h2>dev的h2</h2>
    <h3>dev的h3</h3>
    <router-view/>
  </div>
</template>

<script>
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
</style>
