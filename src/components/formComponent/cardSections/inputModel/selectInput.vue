<template>
  <v-select
    :items="itemlist"
    :label="fieldlable"
    dense
    :rules="[v => !!v || 'Item is required']"
  ></v-select>
</template>
<script>
export default {
  props: {
    itemlist: [],
    fieldlabel: {
      required: true
    }
  }
};
</script>
