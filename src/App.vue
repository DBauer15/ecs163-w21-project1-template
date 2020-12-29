<!-- This file will be used to layout and connect your views -->
<template>
  <div id="app">
      <View1 />
      <View2 />
  </div>
</template>

<script>
import View1 from './components/View1.vue'
import View2 from './components/View2.vue'

export default {
  name: 'App',
  components: {
    View1,
    View2
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
