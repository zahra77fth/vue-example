<template>
    <h2 class="headTitle">{{ title }}</h2>
</template>

<script>
export default ({
props:{
    title : {
        type : String
    }
}
})
</script>
<style>
.headTitle{
    font-weight: 80 !important;
    padding:25px 10%;
    margin: 0px;
    font-size: 1.5em;
}
</style>