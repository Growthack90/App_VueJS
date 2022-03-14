<template>
  <div id="app">
    <h1>App Vue</h1>
<ComponentHeader />    
<ComponentBody />
<ComponentFooter /> 
  </div>
</template>

<script>
import ComponentHeader from '@/components/ComponentHeader.vue'
import ComponentBody from '@/components/ComponentBody.vue'
import ComponentFooter from '@/components/ComponentFooter.vue'

export default {
  name: 'app',
  components: {
    ComponentHeader,
    ComponentBody,
    ComponentFooter,
  },
}
</script>

<style>

* {
  font-family: Arial, Helvetica, sans-serif;
}

</style>