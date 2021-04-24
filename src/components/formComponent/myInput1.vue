<template>
<div id="input">
      <input
        class="input"
        type="text"
        :id="id"
        :label="label"
        :required="required"
      />
      </div>
</template>

<script>  export default {
    props: {
      id: {
        type: String
      },
      label: {
        type: String,
        required: true
      },
      required: {
        type: Boolean,
        default: false
      }
    }
    }
</script>

<style>
#input{
  width: 45%;
}
.input{
  border: 0;
  margin: 18px;
  border-bottom: 3px solid rgb(12, 32, 71);
  background-color: white;
}
.vs-input{
  background-color: white;
}
</style>