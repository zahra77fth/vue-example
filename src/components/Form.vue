<template>
      <v-form>
        <addPhoto />
        <name />
        <basicInfo :gender="gender" :years="years" :months="months" />
        <militaryStatus :military="military" />
        <marriageStatus :marriage="marriage" :majors="majors" />
        <contactInfo  />
        <education :majors="majors" :years="years" />
        <computerSkill />
        <accent />
        <language />
        <expriance :years="years" :months="months" />
        <reference />
        <favoriteDepartment />
        <complementaryQuestion :introduction="introduction" />
        <submit/>      
      </v-form>
</template>



<script>
import addPhoto from './fromGroup/addPhoto'
import name from './fromGroup/secrion1-name'
import basicInfo from './fromGroup/secrion2-basicInfo'
import militaryStatus from './fromGroup/secrion3-militaryStatus'
import marriageStatus from './fromGroup/secrion4-marriageStatus'
import contactInfo from './fromGroup/secrion5-contactInfo'
import education from './fromGroup/secrion6-education'
import computerSkill from './fromGroup/secrion7-computerSkill'
import accent from './fromGroup/secrion8-accent'
import language from './fromGroup/secrion9-language'
import expriance from './fromGroup/secrion10-expriance'
import reference from './fromGroup/secrion11-reference'
import favoriteDepartment from './fromGroup/secrion12-favoriteDepartment'
import complementaryQuestion from './fromGroup/secrion13-complementaryQuestion'
import Submit from './fromGroup/submit'
export default {
  components: {
    name,
    basicInfo,
    militaryStatus,
    marriageStatus,
    contactInfo,
    education,
    computerSkill,
    accent,
    language,
    expriance,
    reference,
    favoriteDepartment,
    complementaryQuestion,
    Submit,
    addPhoto
  },
  data: () => ({
    gender: ['مرد', 'زن'],
    years: ['۱۳۴۰', '۱۳۴۱','۱۳۴۲','۱۳۴۳','۱۳۴۴','۱۳۴۵','۱۳۴۶','۱۳۴۷','۱۳۴۸','۱۳۴۹','۱۳۵۰','۱۳۵۱','۱۳۵۲','۱۳۵۳','۱۳۵۴','۱۳۵۵','۱۳۵۶','۱۳۵۷','۱۳۵۸','۱۳۵۹','۱۳۶۰','۱۳۶۱','۱۳۶۲','۱۳۶۳','۱۳۶۴','۱۳۶۵','۱۳۶۶','۱۳۶۷','۱۳۶۸','۱۳۶۹','۱۳۷۰','۱۳۷۱','۱۳۷۲','۱۳۷۳','۱۳۷۴','۱۳۷۵','۱۳۷۶','۱۳۷۷','۱۳۷۸','۱۳۷۹','۱۳۸۰','۱۳۸۱','۱۳۸۲','۱۳۸۳','۱۳۸۴','۱۳۸۵','۱۳۸۶','۱۳۸۷','۱۳۸۸', '۱۳۸۹','۱۳۹۰','۱۳۹۱','۱۳۹۲','۱۳۹۳','۱۳۹۴','۱۳۹۵','۱۳۹۶','۱۳۹۷','۱۳۹۸','۱۳۹۹','۱۴۰۰'],
    months: ['فروردین','اردیبهشت','خرداد','تیر','مرداد','شهریور','مهر','آبان','آذر','دی','بهمن','اسفند'],
    militaryStatus: ['معافیت پزشکی','معافیت سایر','پایان طرح خدمت','در حال اتمام','در حال گذراندن','هنوز شروع نشده'],
    marriage: ['متاهل','مطلقه','مجرد'],
    majors: ['متخصص و PHD','دکترا حرفه ای','کارشناسی ارشد','کارشناسی','فوق دبپلم','دیپلم','سایر'],
    introduction: ['Linkedin Ads', 'IranTallent Ads', 'Congresses', 'Introduced By Someone', 'Heard about in the Business', 'University departments & Forums', 'Other'],
    rules: {
        required: value => !!value || 'فیلد اجباری'
    }
  }),
};
</script>

<style>


</style>