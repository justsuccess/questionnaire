<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  	name: 'app'
}
</script>

<style>
html,body,#app{height: 100%;width:100%;}
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  overflow-x:hidden;
}
</style>
