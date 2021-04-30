<template>
  <v-form class="text-right">
    <v-container>
      <myhead mytitle="نام شما"></myhead>
      <v-row>
        <v-col class="dj" cols="12" md="6">
          <myInput value="نام"></myInput>
        </v-col>

        <v-col cols="12" md="6">
          <myInput value="Name"></myInput>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="12" md="6">
          <myInput value="نام خانوادگی"></myInput>
        </v-col>

        <v-col cols="12" md="6">
          <myInput value="Last Name"></myInput>
        </v-col>
      </v-row>
    </v-container>
  </v-form>
</template>

<script>
import myhead from "./inputModel/headcard.vue";
import myInput from "./inputModel/textInput";

export default {
  components: {
    myhead,
    myInput
  }
};
</script>
