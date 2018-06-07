<template>
  <div id="app">
    <img src="./assets/logo.png">
    <PlayerList/>
    <HelloWorld msg="Hey, Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import PlayerList from './components/PlayerList.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    PlayerList
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
