<template>
  <div id="app">
    <Hangman/>
  </div>
</template>

<script>
import Hangman from './components/Hangman'

export default {
  name: 'App',
  components: {
    Hangman
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;  
  background-color: #2c3e50;
}
</style>
