<template>
  <div id="app">
    <img src="./assets/logo.png">
    <button @click="aaa">ssss</button>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App',
  methods: {
    aaa: function () {
      alert('aa')
    }
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
