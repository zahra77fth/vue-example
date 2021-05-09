<template>
  <v-form class="text-right">
    <groupTitle title="سوالات تکمیلی"></groupTitle>
      <v-row>
          <selectInput :items="introduction" fieldlable="نحوه اشنایی با ارکید فارمد"></selectInput>
      </v-row>
      <v-row>
        <textInput value=" حقوق پیشنهادی شما (اجباری)"></textInput>
      </v-row>
      <v-row>
        <textInput value="سابقه جراحی - بیماری" ></textInput>
      </v-row>
      <v-row>
          <textInput value="آیا در شرکت های همکار یا رقیب ارکید فارمد کسی را میشناسید ؟"></textInput>
      </v-row>
  </v-form>
</template>

<script>
import groupTitle from "./inputModel/groupTitle.vue";
import textInput from "./inputModel/textInput"
import selectInput from './inputModel/selectInput.vue';
export default {
  components: {
    groupTitle,
    textInput,
    selectInput
  },
  props:["introduction"]
};
</script>