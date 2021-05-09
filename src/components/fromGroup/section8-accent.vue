<template>
  <v-form class="text-right">
    <groupTitle title="آشنایی با لهجه های محلی"></groupTitle>
      <v-row>
        <v-col cols="12" md="4">
          <checkBox label="کردی"></checkBox>
        </v-col>

        <v-col cols="12" md="4">
          <checkBox label="ترکی"></checkBox>
        </v-col>
      </v-row>
      <v-row>
          <textInput value="آیا با گویش دیگری اشنایی دارید ؟"></textInput>
      </v-row>
  </v-form>
</template>

<script>
import groupTitle from "./inputModel/groupTitle.vue";
import checkBox from "./inputModel/checkBox";
import textInput from "./inputModel/textInput"
export default {
  components: {
    groupTitle,
    checkBox,
    textInput
  }
};
</script>