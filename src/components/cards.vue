<template>
  <div class="card">
    <div class="cricles">
      <div class="human-icon">
        <img class="cricle" src="@/assets/images/Vector.svg">
        <img class="human-body" src="@/assets/images/Vector (1).svg">
      </div>
    </div>
    <div class="info">
      <span>Jismoniy Shaxslar uchun</span>
    </div>
  </div>
</template>

<script>
export default {
  components: {
    
  }
}
</script>

<style scoped>
.card {
    /* display: flex; */
    width: 226px;
    height: 303px;
    background: #FFFFFF;
    border-radius: 20px;
}
.cricles{
  width: 80px;
  height: 80px;
  background: #1B66F3;
  border-radius: 40px;
  position: relative;
  margin: 20px;
  display: flex;
  justify-content: center;
  align-items: center;
}
.cricle {
    position: relative;
    bottom: 10px;
    left: 13px;
}
.human-body {
    position: relative;
    top: 8px;
    right: 7px;
}
.human-icon {
  
}
</style>