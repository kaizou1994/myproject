<template>
  <div id="app">
    <Category></Category>
    <Mine></Mine>
  </div>
</template>

<script>

import Category from './pages/category/Category'
import Mine from './pages/mine/Mine'

export default {
  name: 'app',
  components: {
    Category,Mine
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
