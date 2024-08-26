<template>
  <h1>From app</h1>
  <CounterComponent />
</template>

<script>
import CounterComponent from './components/Counter.vue'

export default {
  name: 'App',
  components: {
    CounterComponent // Updated to match the new component name
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
