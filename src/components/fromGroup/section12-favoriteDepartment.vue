<template>
  <v-form>
    <groupTitle title="زمینه های کاری مورد علاقه"></groupTitle>
    <v-row>
      <v-col cols="12" md="3">
        <checkBox label="مارکتینگ علمی"></checkBox>
      </v-col>
      <v-col cols="12" md="3">
        <checkBox label="مدیکال انفورماتیک"></checkBox>
      </v-col>
      <v-col cols="12" md="3">
        <checkBox label="فناوری اطللاعات"></checkBox>
      </v-col>
      <v-col cols="12" md="3">
        <checkBox label="پشتیبانی بیماران"></checkBox>
      </v-col>
      <v-col cols="12" md="3">
        <checkBox label="منابع انسانی"></checkBox>
      </v-col>
    </v-row>
  </v-form>
</template>

<script>
import groupTitle from "./inputModel/groupTitle"
import checkBox from "./inputModel/checkBox"
export default {
  components: {
    checkBox ,
    groupTitle
  }
};
</script>