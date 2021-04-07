
<template>
    <div class="center form-container">
    <h2 class="section-name your-name">Your Name</h2>
    <input1 v-model="name" label="Name" :required="true" id="name" />
    <input1 v-model="lastName" label="Last name" :required="true" id="lastname" />
    <input1 v-model="name" label="Name" :required="true" id="name" />
    <input1 v-model="name" label="Name" :required="true" id="name" />
    </div>
</template>

<script>
import Vue from 'vue'
import Vuesax from 'vuesax'
Vue.use(Vuesax, {
    // options here
  })
import input1 from './formComponent/myInput1.vue'
    export default {
      data:() => ({
        value: ''
      }),
    components: {
      input1
  }
    }
</script>

<style>
.form-container{
display: flex;
justify-content: space-between;
flex-wrap: wrap;
width: 70vw;
}
.section-name{
width: 100%;
text-align: left;
}
</style>