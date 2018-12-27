<template lang="html">
  <div class="home main-content">
    <div class="left-content">
      <h1>20 YRS DESIGN</h1>
      <p class="subtxt">Amadou is an ..........</p>
      <p class="subtxt">Amadou is an ..........</p>
    </div>
    <div class="right-content img1">
      <button><router-link :to="/portfolio/one">Browse Work</router-link></button>
    </div>
  </div>
</template>

<script>
export default {
  name : "Home"
}
</script>

<style scoped>
.img1{
  background: url('../assets/home.jpg')
}
</style>
