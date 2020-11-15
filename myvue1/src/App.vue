<template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view/>
    <div id = 'appBelow'>
    </div>
    <div id = 'appBelow'>
    </div>
    <router-view/>
     <router-view/>
      <router-view/>
       <router-view/>
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
#appBelow{
  width : 200px;
  height: 600px;
  background-color: red;
  float: left;
}
</style>
