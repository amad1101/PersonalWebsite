<template>
  <div class="app">

  </div>
</template>

<script>
export default {
  name: 'App',
};
</script>

<style>
.app {
  position: relative;
  width: 100%;
  height: 400px;
  background: #7A39DB;
  /* box-sizing: border-box;
  padding: 30px;
  margin-bottom: 100px; */
  opacity: 50%;
}
.app:after{
  position: absolute;
  width: 100%;
  height: 100%;
  content: '';
  background: inherit;
  z-index: -1;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  transform-origin: top right;
  transform: skewY(-4deg);
  opacity: 50%;
}
</style>
