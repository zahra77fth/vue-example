<template>
  <div id="cardGroup">
    <div class="card">
      <myhead mytitle="ثبت تصویر"></myhead>
    </div>
    <div class="card">
      <sec1></sec1>
    </div>
    <div class="card">
      <sec2></sec2>
    </div>
    <div class="card">
      <sec3></sec3>
    </div>
    <div class="card">
      <sec4></sec4>
    </div>
    <sec5></sec5>
    <div class="card">
      <sec6></sec6>
    </div>
    <div class="card">
      <sec7></sec7>
    </div>
    <div class="card">
      <sec8></sec8>
    </div>
    <div class="card">
      <sec9></sec9>
    </div>
    <div class="card">
      <sec10></sec10>
    </div>
    <div class="card">
      <sec11></sec11>
    </div>
    <div class="card">
      <sec12></sec12>
    </div>
    <div class="card">
      <sec13></sec13>
    </div>
    <div class="card">
      <button></button>
    </div>
  </div>
</template>

<script>
import sec1 from "./cardSections/sec1.vue";
import sec2 from "./cardSections/sec2.vue";
import sec3 from "./cardSections/sec3.vue";
import sec4 from "./cardSections/sec4.vue";
import sec5 from "./cardSections/sec5.vue";
import sec6 from "./cardSections/sec6.vue";
import sec7 from "./cardSections/sec7.vue";
import sec8 from "./cardSections/sec8.vue";
import sec9 from "./cardSections/sec9.vue";
import sec10 from "./cardSections/sec10.vue";
import sec11 from "./cardSections/sec11.vue";
import sec12 from "./cardSections/sec12.vue";
import sec13 from "./cardSections/sec13.vue";

export default {
  components: {
    sec1,
    sec2,
    sec3,
    sec4,
    sec5,
    sec6,
    sec7,
    sec8,
    sec9,
    sec10,
    sec11,
    sec12,
    sec13
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
    ],
    military: [
      "معافیت پزشکی",
      "معافیت سایر",
      "پایان طرح خدمت",
      "در حال اتمام",
      "در حال گذراندن",
      "هنوز شروع نشده"
    ],
    marriage: ["متاهل", "مطلقه", "مجرد"],
    majors: [
      "متخصص و PHD",
      "دکترا حرفه ای",
      "کارشناسی ارشد",
      "کارشناسی",
      "فوق دبپلم",
      "دیپلم",
      "سایر"
    ],
    introduction: [
      "Linkedin Ads",
      "IranTallent Ads",
      "Congresses",
      "Introduced By Someone",
      "Heard about in the Business",
      "University departments & Forums",
      "Other"
    ],
    rules: {
      required: value => !!value || "فیلد اجباری"
    }
  })
};
</script>
<style>
.card {
  width: 100%;
  margin: 5px 0px;
  padding: 20px 10%;
  box-sizing: border-box;
  background: linear-gradient(180deg, #f1f5f8 0%, #ffffff 100%);
  overflow: hidden;
  display: block;
  color: #c1ced9;
  font-family: "text";
}
#cardGroup {
  width: 100vw;
}
</style>
