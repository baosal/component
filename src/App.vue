<template>
  <div id="app">
    <CardGroup/>
  </div>
</template>

<script>
import CardGroup from './components/CardGroup.vue'

export default {
  name: 'App',
  components: {
    CardGroup
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
