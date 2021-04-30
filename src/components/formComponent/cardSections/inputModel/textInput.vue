<template>
  <v-text-field
    class="textsize"
    color="#264F7E"
    v-model="fname"
    :rules="reqRules"
    :label="value"
    dir="rtl"
    required
  ></v-text-field>
</template>
<script>
export default {
  data: () => ({
    valid: false,
    default: "",
    reqRules: [v => !!v || ""]
  }),
  props: {
    value: {
      required: true
    }
  }
};
</script>
<style></style>
