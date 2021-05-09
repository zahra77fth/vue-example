<template>
  <v-form class="text-right">
    <groupTitle title="اطلاعات اولیه"></groupTitle>
      <v-row>
        <v-col cols="12" md="6">
          <textInput value="جنسیت (اجباری)"></textInput>
        </v-col>

        <v-col cols="12" md="6">
          <textInput value="نام پدر (اجباری)"></textInput>
        </v-col>
        <v-col cols="12" md="6">
          <textInput value="شماره شناسنامه (اجباری)"></textInput>
        </v-col>

        <v-col cols="12" md="6">
          <textInput value="کد ملی (اجباری)"></textInput>
        </v-col>
        <v-col cols="12" md="3">
            <selectInput fieldlable="سال (اجباری)" :items="years"></selectInput>
        </v-col>
        <v-col cols="12" md="6">
            <selectInput fieldlable="ماه (اجباری)" :items="months"></selectInput>
        </v-col>
        <v-col cols="12" md="3">
            <textInput value="روز (اجباری)"></textInput>
        </v-col>
        <v-col cols="12" md="3">
            <selectInput fieldlable="سال (اجباری)" :items="years"></selectInput>
        </v-col>
        <v-col cols="12" md="6">
            <selectInput fieldlable="ماه (اجباری)" :items="months"></selectInput>
        </v-col>
        <v-col cols="12" md="3">
            <textInput value="روز (اجباری)"></textInput>
        </v-col>
      </v-row>
  </v-form>
</template>

<script>
import groupTitle from "./inputModel/groupTitle.vue";
import textInput from "./inputModel/textInput";
import selectInput from "./inputModel/selectInput"
export default {
  components: {
    groupTitle,
    textInput,
    selectInput
  },
  props: ["months",'years']
};
</script>