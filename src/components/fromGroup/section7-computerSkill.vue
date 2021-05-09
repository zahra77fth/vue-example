<template>
  <v-form class="text-right">
    <groupTitle title="Computer Sills"></groupTitle>
      <v-row>
        <v-col cols="12" md="4">
          <checkBox label="Word"></checkBox>
        </v-col>

        <v-col cols="12" md="4">
          <checkBox label="Outlook"></checkBox>
        </v-col>
        <v-col cols="12" md="4">
          <checkBox label="Excel"></checkBox>
        </v-col>
        <v-col cols="12" md="4">
          <checkBox label="Medical Search"></checkBox>
        </v-col>
        <v-col cols="12" md="4">
          <checkBox label="Power Point"></checkBox>
        </v-col>
        <v-col cols="12" md="4">
          <checkBox label="Fast Typing"></checkBox>
        </v-col>
          <textInput value="آیا با مهارت کامپیوتری دیگری اشنایی دارید ؟"></textInput>
      </v-row>
  </v-form>
</template>

<script>
import groupTitle from "./inputModel/groupTitle";
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