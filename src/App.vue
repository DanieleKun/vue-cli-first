<template>
  <div id="app">
    <HelloWorld/>
    <JumboTron/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import JumboTron from './components/Jumbotron.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    JumboTron
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
