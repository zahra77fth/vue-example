<template>
  <v-form class="text-right">
    <groupTitle title="اطلاعات تماس"></groupTitle>
      <v-row>
        <v-col cols="12" md="6">
          <textInput value="تلفن (اجباری)"></textInput>
        </v-col>
        <v-col cols="12" md="6">
          <textInput value="موبایل (اجباری)"></textInput>
        </v-col>
        <v-col cols="12" md="6">
          <textInput value="ایمیل (اجباری)"></textInput>
        </v-col>
        <v-col cols="12" md="6">
          <textInput value=" شهر (اجباری)"></textInput>
        </v-col>
        <v-col cols="12" md="12">
            <textInput value=" آدرس (اجباری)"></textInput>
        </v-col>
      </v-row>
  </v-form>
</template>

<script>
import groupTitle from "./inputModel/groupTitle";
import textInput from "./inputModel/textInput";
export default {
  components: {
    groupTitle,
    textInput,
  }
};
</script>