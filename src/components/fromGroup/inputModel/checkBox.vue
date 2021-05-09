
<template>
<div class="checkboxDiv">
  <input type="checkbox" id="id" class="checkbox" >
  <div class="ckeckboxview" v-bind:style="{  background: color }" v-if="!check" @click="changeColor"></div>
  <div class="ckeckboxview" v-bind:style="{  background: color }" v-else @click="changeBack"></div>
  <label class="label">{{ label }}</label>
</div>
</template>
<script>
export default {
    data:() => ({
        color: '#c1ced9',
        check: false
}),
 props: {
   'label':{
     type : String
   }
 },
 methods:{
     changeColor: function() {
        this.color = "#264F7E",
        this.check = true
            
     },
     changeBack: function() {
        this.color = '#c1ced9'
        this.check = false
     }
 }
};
</script>
<style>
.checkboxDiv{
    display: flex;
    align-items: center;
}
.checkbox {
  width: 18px;
  height: 18px;
  position: relative;
  margin: 6px;
  background: #c1ced9 !important;

}
.checkbox:checked {

  background: #264F7E !important;
    color: #264F7E;
}
.ckeckboxview{
    border-radius: 5px;
    background: #c1ced9;
    position: absolute;
    height: 20px;
    width: 20px;
    margin: 5px;
    z-index: 1;
}
</style>