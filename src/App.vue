<template>
  <div id="app">
    <flavor-display />
    <flavor-form />
  </div>
</template>

<script>
import FlavorDisplay from './components/FlavorDisplay.vue'
import FlavorForm from './components/FlavorForm.vue'

export default {
  name: 'app',
  components: {
    FlavorDisplay,
    FlavorForm
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
  margin-top: 60px;
}
</style>
