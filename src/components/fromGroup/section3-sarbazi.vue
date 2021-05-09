<template>
  <v-form class="text-right">  
    <groupTitle title="طرح و سربازی"></groupTitle>
      <v-row>
        <v-col cols="12" md="6">
          <selectInput fieldlable="وضعیت سربازی" :items="sarbazi"></selectInput>
        </v-col>
        <v-col cols="12" md="6">
          <textInput value="علت معافیت"></textInput>
        </v-col>
      </v-row>
  </v-form>
</template>

<script>
import groupTitle from "./inputModel/groupTitle";
import textInput from "./inputModel/textInput";
import selectInput from "./inputModel/selectInput"
export default {
  components: {
    groupTitle,
    textInput,
    selectInput
  },
  props: ['sarbazi']
};
</script>