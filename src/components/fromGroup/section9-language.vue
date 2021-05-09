<template>
  <v-form class="text-right">
    <groupTitle title="زبان های خارجی"></groupTitle>
      <v-row>
        <v-col cols="12" md="4">
          <checkBox label="IELTS"></checkBox>
        </v-col>
        <v-col cols="12" md="4">
          <checkBox label="TOEFL"></checkBox>
        </v-col>
        <v-col cols="12" md="4">
          <checkBox label="GRE"></checkBox>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="12" md="4">
          <checkBox label="English Intermediate"></checkBox>
        </v-col>
        <v-col cols="12" md="4">
          <checkBox label="English Beginner"></checkBox>
        </v-col>
        <v-col cols="12" md="4">
          <checkBox label="French Advanced"></checkBox>
        </v-col>
      </v-row>
            <v-row>
        <v-col cols="12" md="4">
          <checkBox label="French Intermediate"></checkBox>
        </v-col>
        <v-col cols="12" md="4">
          <checkBox label="French Beginner"></checkBox>
        </v-col>
      </v-row>
      <v-row>
          <textInput value="آیا با زبان خارجی دیگری اشنایی دارید ؟"></textInput>
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