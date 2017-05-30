<template>
  <div id="app">
    <h1>我是首页</h1>
    <h2><a href="detail.html">点我跳转详情页</a></h2>
    <img src="../../assets/logo.png">
    <hello></hello>
  </div>
</template>

<script>
import Hello from '../../components/Hello'

export default {
  name: 'app',
  components: {
    Hello
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
