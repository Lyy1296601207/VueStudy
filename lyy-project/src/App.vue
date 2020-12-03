<!--
 * @Descripttion: 
 * @version: 
 * @Author: yangyang.liu
 * @Date: 2020-12-03 16:57:56
 * @LastEditors: yangyang.liu
 * @LastEditTime: 2020-12-03 17:07:18
-->
<template>
  <div id="app">
    <img src="./assets/logo.png">
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
</style>
