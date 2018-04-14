<template>
  <div id="app">
    <img src="./assets/logo.png">
    <message-form />
  </div>
</template>

<script>
import MessageForm from './components/MessageForm'

export default {
  name: 'app',
  components: {
    MessageForm
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
