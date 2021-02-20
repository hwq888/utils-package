<template>
  <div id="app">
    <p>utils-package服务已启动</p>
  </div>
</template>

<script>
import { test } from './index'
export default {
  name: 'App',
  mounted () {
    test.getNowTime()
    test.showMessage('打印一段msg')
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
