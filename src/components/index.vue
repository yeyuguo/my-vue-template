<template>
  <div>
      <Header v-bind:props_msg="headerMsg" />
      <Body v-bind:props_msg="bodyMsg" />
      <Footer v-bind:props_msg="footerMsg" />
  </div>
  
</template>


<script>
import Header from "./common/header";
import Footer from "./common/footer";
import Body from './common/body'
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
    Body
  }
};
</script>
