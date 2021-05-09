<template>
  <v-form class="text-right">
    <groupTitle title="سوابق شغلی"></groupTitle>
      <v-row>
        <v-col cols="12" md="6">
          <textInput value="عنوان شغلی (اجباری)"></textInput>
        </v-col>
        <v-col cols="12" md="6">
          <textInput value="عنوان شغلی (اجباری)"></textInput>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="12" md="3">
          <selectInput :items="months" fieldlable="ماه ورود (اجباری)"></selectInput>
        </v-col>
        <v-col cols="12" md="3">
          <selectInput :items="years" fieldlable=" سال ورود (اجباری)"></selectInput>
        </v-col>
        <v-col cols="12" md="3">
          <selectInput :items="months" fieldlable="(اجباری) ماه خروج"></selectInput>
        </v-col>
        <v-col cols="12" md="3">
          <selectInput :items="years" fieldlable="(اجباری) سال خروج"></selectInput>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="12" md="6">
          <textInput value="علت تغییر(اجباری)"></textInput>
        </v-col>
      </v-row>
  </v-form>
</template>

<script>
import groupTitle from "./inputModel/groupTitle.vue";
import selectInput from "./inputModel/selectInput";
import textInput from "./inputModel/textInput"
export default {
  components: {
    groupTitle,
    selectInput,
    textInput
  },
  props:["years","months"]
};
</script>