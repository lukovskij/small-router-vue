<template>
  <div id="app">
     <router-link to="/">Home</router-link>
    <router-link to="/about">About</router-link>
    <router-link to="/coins/bitcoin">bitcoin</router-link>
    <router-link to="/coins/ethereum">ethereum</router-link>
    <img src="./assets/logo.png">
    <router-view></router-view>
  </div>
</template>

<script>
import About from '@/components/About'
import Hello from '@/components/Hello'
export default {
  name: 'app'
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
img{
  display: block;
  margin: 0 auto;
  margin-top: 20px;
}
</style>
