<template>
  <footer>
      <HR/>
    <div v-text="props_msg"></div>
    <div v-text="data_msg"></div>
    <div>{{compute_msg}}</div>
  </footer>
</template>



<script>
export default {
  name: "Footer",
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
