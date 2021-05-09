<template>
  <v-text-field
    class="textsize pa-0 ma-0 text-right textcolor"
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
<style>
  .my-text-style >>> .v-text-field__slot input {
    color: #c1ced9 !important;
  }
  .theme--light{
    color: #c1ced9!important;
  }
  .textcolor input{
    color: #264F7E !important;
  }
  .theme--light.v-input {
    color: #264F7E !important;
    }

    .v-text-field.v-input--has-state > .v-input__control > .v-input__slot:before {
    border-color: currentColor !important;
}
.v-text-field > .v-input__control > .v-input__slot:before {
    border-color: #c1ced9 !important;
    border-style: solid;
    border-width: 2px 0 0 0 !important;
}
.v-text-field > .v-input__control > .v-input__slot:before, .v-text-field > .v-input__control > .v-input__slot:after {
    bottom: -1px;
    content: "";
    left: 0;
    position: absolute;
    transition: 0s cubic-bezier(0, 0, 0, 1) !important;
    width: 100%;
}
::before, ::after {
    text-decoration: inherit !important;
    vertical-align: inherit !important;
}
*, ::before, ::after {
    background-repeat: no-repeat;
    box-sizing: inherit;
}
</style>
