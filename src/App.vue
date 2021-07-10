<template>
  <div id="app">
    <baseHeader/>
    <maincontainer/>
    
  </div>
</template>

<script>
import baseHeader from './components/baseHeader.vue'
import maincontainer from './components/maincontainer.vue'

export default {
  name: 'App',
  components: {
    baseHeader,
    maincontainer
  }
}
</script>

<style>
@import url(./assets/styles/reset.css);
@import url(./assets/fonts/Poppins-SemiBold.ttf);

</style>
