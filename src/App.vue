<template>
  <div id="app">
    <Head />
    <Form />
  </div>
</template>

<script>
import Vue from "vue";
import Vuesax from "vuesax";
import "vuesax/dist/vuesax.css"; //Vuesax styles
Vue.use(Vuesax, {
  // options here
});
import Head from "./components/Head.vue";
import Form from "./components/Form.vue";
export default {
  name: "App",
  components: {
    Head,
    Form
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: right;
  width: 100vw;
}
</style>
