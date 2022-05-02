<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Main-Title />
    <MyJumbo/>
 
  </div>
</template>

<script>
import MainTitle from './components/Main-Title.vue'
import MyJumbo from './components/My-Jumbo.vue'

export default {
  name: 'App',
  components: {
    MainTitle,
    MyJumbo
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
