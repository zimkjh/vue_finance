<template>
  <div id="app">
    <router-view/>
    <h2>Hello world!</h2>
    <marquee>HEY</marquee>
    <div id="app2">
      {{message}}
    </div>
  </div>
</template>

<script>
export default {
  name: 'App'
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
