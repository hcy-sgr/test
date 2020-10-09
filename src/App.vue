<template>
  <div id="app">
    <div>我修改了</div>
  <div>6666</div>
  <div>我也修改了</div>
    <h2>master的h2</h2>
    <h1>我还是修改了</h1>
    <h3>master的h3</h3>
    <h2>dev的h2</h2>
    <h3>dev的h3</h3>
    <span>dev的span</span>
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
