<template>
<div id="cardGroup">
    <div class="card">
        <myhead mytitle='ثبت تصویر'>
        </myhead>
    </div>
        <div class="card">
        <myhead mytitle='نام شما'></myhead>
    </div>
        <div class="card">
        <myhead mytitle='اطلاعات اولیه'></myhead>
    </div>
        <div class="card">
        <myhead mytitle='طرح و سربازی'></myhead>
    </div>
        <div class="card">
        <myhead mytitle='تاهل'></myhead>
    </div>
        <div class="card">
        <myhead mytitle='اطلاعات تماس'></myhead>
    </div>
        <div class="card">
        <myhead mytitle='سوابق تحصیلی (لطفا از آخرین مقطع تحصیلی شروع کنید)'></myhead>
    </div>
        <div class="card">
        <myhead mytitle='Computer Skills'></myhead>
    </div>
        <div class="card">
        <myhead mytitle='آشنایی با لهجه های محلی'></myhead>
    </div>
        <div class="card">
        <myhead mytitle='زبان های خارجی'></myhead>
    </div>
        <div class="card">
        <myhead mytitle='سوابق شغلی'></myhead>
    </div>
        <div class="card">
        <myhead mytitle='معرف'></myhead>
    </div>
        <div class="card">
        <myhead mytitle='زمینه های کاری مورد علاقه'></myhead>
    </div>
        <div class="card">
        <myhead mytitle='سوالات تکمیلی'></myhead>
    </div>
        <div class="card">
        <button></button>
    </div>
    </div>
</template>

<script>
import myhead from './headcard.vue'
export default {
          components: {
        myhead
      }
}
</script>
<style>
.card{
    width: 100%;
    margin: 5px 0px;
    padding: 20px 10%;
    box-sizing: border-box;
    background: linear-gradient(180deg, #f1f5f8 0%, #f1f5f8 100%);
    overflow: hidden;
    display: block;
    color: #c1ced9;
    font-family:'text';
}
.myhead{
    direction: rtl;
    margin: 0px 15px;
    display: block;
    font-size: 1.5em;
    margin-block-start: 0.83em;
    margin-block-end: 0.83em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;
}

</style>