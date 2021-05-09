<template>
  <v-combobox
    class="pa-0 ma-0 pt-2 text-right textcolor"
    :items="items"
    :label="fieldlable"
    dense
    color="#264F7E"
    :rules="[v => !!v || 'Item is required']"
  ></v-combobox>
</template>
<script>
export default {
 props: ['items', 'fieldlable']
};
</script>
<style>
  .textcolor input{
    color: #264F7E !important;
  }
</style>