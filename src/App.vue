<template>
  <div id="app">
    <h1>Vue.js Component LifeCycle Hooks</h1>
    <h4>{{counter}}</h4>
    <button @click="counter++">Increase</button>
  </div>
</template>

<script>

export default {
  name: 'App',
  data: function(){
    return {
      counter: 0
    }
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
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
</style>
