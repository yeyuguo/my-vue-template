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




<style lang="less" scoped>
// 全局使用的 基础样式
@import url('./style/common/basic.less'); 
@import url('./style/index.less');

body{
  // mac-pro : (client/320)*20 px = 1rem == 25px
  font-size: 1rem;
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

