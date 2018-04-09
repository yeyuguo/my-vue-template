<template>
  <div id="body">
      <div v-text="props_msg">{{props_msg}}</div>
  </div>
</template>


<script>
export default {
  name:'Body',
  props:['props_msg'],
  data(){
      return {
          msg:"这是内容部分"
      }
  }
}
</script>



<style lang="less" scoped>

</style>
