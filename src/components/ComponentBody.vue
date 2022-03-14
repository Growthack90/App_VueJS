<template>
  <div id="component-body">
<h2>Body</h2>
<Form />
  </div>
</template>

<script>
import Form from './Form.vue'

  export default {
    name: 'component-body',
    components: {
      Form,
    }
  }
</script>

<style scoped>
  h2 {
  background-color: red;
  color: green;
  padding: 40px;
  text-align: center;
  border: 5px solid black;
  }
</style>