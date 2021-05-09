<template>
  <v-form class="text-right">
    <groupTitle title="تاهل"></groupTitle>
      <v-row>
        <v-col cols="12" md="6">
          <selectInput fieldlable="وضعیت (اجباری)" :items="marriage"></selectInput>
        </v-col>
        <v-col cols="12" md="6">
          <selectInput fieldlable="تحصیلات همسر" :items="majors"></selectInput>
        </v-col>
        <v-col cols="12" md="6">
          <textInput value="شغل همسر"></textInput>
        </v-col>

        <v-col cols="12" md="6">
          <textInput value="تعداد فرزندان"></textInput>
        </v-col>
        <v-col cols="12" md="6">
            <textInput value="افراد تحت تکفل"></textInput>
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
  props: ["majors",'marriage']
};
</script>