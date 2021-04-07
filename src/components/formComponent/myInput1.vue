<template>
<div id="input">
      <vs-input
        class="input"
        type="text"
        :id="id"
        :label-placeholder="label"
        :value="value"
        :required="required"
        v-on:input="updateValue($event.target.value)"
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
      value: {
        type: String
      },
      required: {
        type: Boolean,
        default: false
      }
    },

    methods: {
      updateValue: function (value) {
        this.$emit('input', value)
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