<template>
  <div id="app">
    <Greetings />
  </div>
</template>

<script>
import Greetings from './components/Greetings'

export default {
  name: 'App',
  components: {
    Greetings
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
  margin-top: calc(100vh - 450px);
}
</style>
