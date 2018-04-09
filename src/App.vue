<template>
  <div id="app">
    <!-- logo -->
    <!-- <img src="./assets/logo.png"> -->
    <router-view/>
  </div>
</template>

<script>
export default {
  name: "App"
};
</script>




<style lang="less">
// 全局使用的 基础样式
@import url("./style/common/basic.less");
@import url("./style/index.less");

body {
  // mac-pro : (client/320)*20 px = 1rem == 25px
  // font-size: 1rem;

  // 为了后面使用方面，统一的把字体都设置为  0.5rem
  header,footer,#body{
    font-size: 0.5rem;
  }
}

#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
}
</style>

