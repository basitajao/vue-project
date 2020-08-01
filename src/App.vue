<template>
  <div id="app">
    <myname message="Basit Ajao" />
  </div>
</template>

<script>
import myname from './components/myname.vue'

export default {
  name: 'App',
  components: {
    myname
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