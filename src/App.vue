<template>
  <v-app>
    <v-main>
      <Head />
      <Form/>
    </v-main>
  </v-app>
</template>

<script>
import Form from './components/Form';
import Head from './components/Head';

export default {
  name: 'App',

  components: {
    Form,
    Head
  },

  data: () => ({
    //
  }),
};
</script>
<style>
#app {
  text-align: right;
  width: 100vw;
}
 @import './assets/style/fontface.css';
  .container {
    padding: 0;
    margin: 0
  }
  .container > .row {
    padding: 0;
  }
  h1 {
    color: #004b70;
    font-size: 25px;
    line-height: 1;
  }
  .welcomeText {
    color: #a0a0a0;
    font-size: 15px;
    margin-bottom: 40px;
  }
  .v-form {
    background: linear-gradient(180deg, #f1f5f8 0%, #ffffff 100%);

  }
  .row{
    padding: 20px 10%;
  }
  #canvas {
    border-radius: 15px;
    box-shadow: rgb(0 0 0 / 20%) 0px 10px 10px;
    border: solid 3px white;
    margin: 50px auto;
    display: block;
    background: white url(./assets/Img/Photo_Icon.png) center center no-repeat;
    cursor: pointer;
  }
  .submit {
    background: #74a55f;
    border-radius: 10px;
    color: white;
    text-align: center;
    padding: 20px 0px !important;
    display: block;
    width: 350px;
    margin: 100px auto 200px auto !important;
    cursor: pointer;
    height: auto !important;
}
</style>