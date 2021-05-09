<template>
  <v-form class="text-right">
    <groupTitle title="معرف"></groupTitle>
      <v-row>
        <v-col cols="12" md="6">
          <textInput value="معرف"></textInput>
        </v-col>
        <v-col cols="12" md="3">
          <textInput value="عنوان شغلی"></textInput>
        </v-col>
        <v-col cols="12" md="3">
          <textInput value="محل فعالیت"></textInput>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="12" md="6">
          <textInput value="معرف"></textInput>
        </v-col>
        <v-col cols="12" md="3">
          <textInput value="عنوان شغلی"></textInput>
        </v-col>
        <v-col cols="12" md="3">
          <textInput value="محل فعالیت"></textInput>
        </v-col>
      </v-row>

  </v-form>
</template>

<script>
import groupTitle from "./inputModel/groupTitle.vue";
import textInput from "./inputModel/textInput"
export default {
  components: {
    groupTitle,
    textInput
  }
};
</script>