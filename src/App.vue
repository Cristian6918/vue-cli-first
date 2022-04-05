<template>
  <div id="app">
    <NewTitle msg="Welcome to Your Vue.js App"/>
    <JumboTron />
  </div>
</template>

<script>
import NewTitle from './components/NewTitle.vue'
import JumboTron from './components/JumboTron.vue'

export default {
  name: 'App',
  components: {
    NewTitle,
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
