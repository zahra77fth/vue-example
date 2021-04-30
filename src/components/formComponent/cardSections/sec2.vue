<template>
  <v-form v-model="valid" class="text-right">
    <v-container>
      <myhead mytitle="اطلاعات اولیه"></myhead>
      <v-row>
        <v-col cols="12" md="6">
          <selectInput :fieldlabel="جنسیت" :itemlist="gender"></selectInput>
        </v-col>

        <v-col cols="12" md="6">
          <myInput value="نام پدر"></myInput>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="12" md="6">
          <myInput value="شماره شناسنامه"></myInput>
        </v-col>

        <v-col cols="12" md="6">
          <myInput value="کد ملی"></myInput>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="12" md="3">
          <selectInput :fieldlabel="جنسیت" :itemlist="gender"></selectInput>
        </v-col>

        <v-col cols="12" md="6">
          <selectInput :fieldlabel="جنسیت" :itemlist="gender"></selectInput>
        </v-col>
        <v-col cols="12" md="3">
          <selectInput value="روز"></selectInput>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="12" md="3">
          <selectInput :fieldlabel="جنسیت" :itemlist="gender"></selectInput>
        </v-col>
        <v-col cols="12" md="6">
          <selectInput :fieldlabel="جنسیت" :itemlist="gender"></selectInput>
        </v-col>
        <v-col cols="12" md="3">
          <selectInput value="روز"></selectInput>
        </v-col>
      </v-row>
    </v-container>
  </v-form>
</template>

<script>
import myhead from "./inputModel/headcard.vue";
import selectInput from "./inputModel/selectInput.vue";
import myInput from "./inputModel/textInput";

export default {
  components: {
    selectInput,
    myInput,
    myhead
  },
  data: () => ({
    gender: ["مرد", "زن"],
    years: [
      "۱۳۴۰",
      "۱۳۴۱",
      "۱۳۴۲",
      "۱۳۴۳",
      "۱۳۴۴",
      "۱۳۴۵",
      "۱۳۴۶",
      "۱۳۴۷",
      "۱۳۴۸",
      "۱۳۴۹",
      "۱۳۵۰",
      "۱۳۵۱",
      "۱۳۵۲",
      "۱۳۵۳",
      "۱۳۵۴",
      "۱۳۵۵",
      "۱۳۵۶",
      "۱۳۵۷",
      "۱۳۵۸",
      "۱۳۵۹",
      "۱۳۶۰",
      "۱۳۶۱",
      "۱۳۶۲",
      "۱۳۶۳",
      "۱۳۶۴",
      "۱۳۶۵",
      "۱۳۶۶",
      "۱۳۶۷",
      "۱۳۶۸",
      "۱۳۶۹",
      "۱۳۷۰",
      "۱۳۷۱",
      "۱۳۷۲",
      "۱۳۷۳",
      "۱۳۷۴",
      "۱۳۷۵",
      "۱۳۷۶",
      "۱۳۷۷",
      "۱۳۷۸",
      "۱۳۷۹",
      "۱۳۸۰",
      "۱۳۸۱",
      "۱۳۸۲",
      "۱۳۸۳",
      "۱۳۸۴",
      "۱۳۸۵",
      "۱۳۸۶",
      "۱۳۸۷",
      "۱۳۸۸",
      "۱۳۸۹",
      "۱۳۹۰",
      "۱۳۹۱",
      "۱۳۹۲",
      "۱۳۹۳",
      "۱۳۹۴",
      "۱۳۹۵",
      "۱۳۹۶",
      "۱۳۹۷",
      "۱۳۹۸",
      "۱۳۹۹",
      "۱۴۰۰"
    ],
    months: [
      "فروردین",
      "اردیبهشت",
      "خرداد",
      "تیر",
      "مرداد",
      "شهریور",
      "مهر",
      "آبان",
      "آذر",
      "دی",
      "بهمن",
      "اسفند"
    ]
  })
};
</script>
