<template>
  <v-form>
    <groupTitle title="نام شما" ></groupTitle>
      <v-row >
        <v-col cols="12" md="6">
          <textInput value="نام"></textInput>
        </v-col>
        <v-col cols="12" md="6">
          <textInput value="Name"></textInput>
        </v-col>
        <v-col cols="12" md="6">
          <textInput value="نام خانوادگی"></textInput>
        </v-col>
        <v-col cols="12" md="6">
          <textInput value="Last Name"></textInput>
        </v-col>
      </v-row>
  </v-form>
</template>

<script>
import groupTitle from "./inputModel/groupTitle";
import textInput from "./inputModel/textInput";

export default{
  components: {
    groupTitle,
    textInput
  }
};
</script>
<style>

</style>