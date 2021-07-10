<template>
  <div class="maincontainer">
    <cards/>
    <cards/>
    <cards/>
    <cards/>
  </div>
</template>

<script>
import cards from './cards.vue'
export default {
  components: {
    cards,
  }

}
</script>

<style  scoped>
.maincontainer {
  width: 100%;
  height: 100%;
  position: fixed;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color:#E5E5E5;
  gap: 20px;
}
</style>