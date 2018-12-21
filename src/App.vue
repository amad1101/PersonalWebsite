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
  background: rgba(40, 40, 40, 0.5);
  box-sizing: border-box;
  padding: 30px;
  margin-bottom: 100px;
}
.app:after{
  position: absolute;
  width: 100%;
  height: 100%;
  content: '';
  background: #ff0000;
  z-index: -1;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  transform-origin: top left;
  transform: skewY(4deg);
}
</style>
