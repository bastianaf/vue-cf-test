<template>
  <div id="app">
    <br><br>
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
     <div class="pt-5">
<Survey> </Survey>
     </div>
      
  </div>

</template>

<script>
import Survey from './components/Survey.vue'

export default {
  name: 'app',
  components: {
    Survey
  }
}
</script>

<style>

</style>
