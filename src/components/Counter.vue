<template>
    <div>
      <h1>Counter</h1>
      <p>Counter: {{ $store.state.counter }}</p>
      <button @click="$store.commit('increment')">Increment</button>
    </div>
  </template>
  
  <script>
  export default {
    name: 'CounterComponent' // Updated to a multi-word name
  }
  </script>
  
  <style scoped>
  </style>
  