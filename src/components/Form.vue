<template>
<div>
<card >
</card>
</div>
</template>

<script>
import Vue from 'vue'
import Vuesax from 'vuesax'
Vue.use(Vuesax, {
    // options here
  })
import card from './formComponent/card.vue'
    export default {
      components: {
        card
      }
    }
</script>
