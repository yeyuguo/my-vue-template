<template>
  <div id="body">
      <div v-text="props_msg"></div>
      <div v-text="data_msg"></div>
      <div>{{compute_msg}}</div>
  </div>
</template>


<script>
export default {
  name: "Body",
  props: ["props_msg"],
  data() {
    return {
      data_msg: `这是 data 获取来的属性值 '${this.props_msg}'`
    };
  },
  computed: {
    compute_msg: function() {
      return `这是 props 获取来的属性值 '${this.props_msg}'`;
    }
  }
};
</script>



<style lang="less" scoped>

</style>
