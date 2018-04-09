<template>
  <div>
      <Header v-bind:props_msg="headerMsg" />
      <div v-text="bodyMsg"></div>
      <Footer v-bind:props_msg="footerMsg" />
  </div>
  
</template>


<script>
import Header from "./common/header";
import Footer from "./common/footer";
export default {
  name: "Index",
  data() {
    return {
      headerMsg: "头信息",
      footerMsg: "底部信息",
      bodyMsg: "这是我的内容"
    };
  },
  components: {
    Header,
    Footer,
  }
};
</script>
