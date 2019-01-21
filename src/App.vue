<template>
  <div id="app">
    <img src="./assets/logo.png">
    <van-icon name="location-o"></van-icon>
    <router-view/>
  </div>
</template>

<script>
  export default {
    name: 'App'
  }
</script>

<style lang="less">
  #app {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
    img {
      border-radius: 50%;
    }
  }
</style>
