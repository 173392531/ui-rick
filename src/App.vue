<template>
  <div id="app">
    <!-- <img src="./assets/logo.png">
    <router-view/> -->
    <rk-button type="login">
      登录
    </rk-button>
    <rk-button type="delete">删除</rk-button>
    <rk-button type="danger">危险</rk-button>
    <rk-button type="primary">私有</rk-button>
    <rk-button type="normal">通用</rk-button>



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
