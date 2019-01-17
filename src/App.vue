<template>
  <div class="app">
    <div class="container">
      <div class="inner">
        <nav>
          <router-link :to="/" id="logo">Amadou Diallo</router-link>


          <ul>
            <li><router-link :to="/">Home</router-link></li>
            <li><router-link :to="/about">About</router-link></li>
            <li><router-link :to="/quotes">Quotes</router-link></li
          </ul>
        </nav>
        <transition name="fade" mode="out-in">
          <router-view />
        </transition>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App',
};
</script>

<style>
/* .app {
  position: relative;
  width: 100%;
  height: 400px;
<<<<<<< HEAD
  background: #7A39DB;
  /* box-sizing: border-box;
=======
  background: #ff0000;
  box-sizing: border-box;
>>>>>>> bb23e9ca1b1189c0f51b45844a29284d4256d8a2
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
<<<<<<< HEAD
  transform-origin: top right;
  transform: skewY(-4deg);
  opacity: 50%;
=======
  transform-origin: 100%;
  transform: skewY(-4deg);
>>>>>>> bb23e9ca1b1189c0f51b45844a29284d4256d8a2
}
body, html {
  margin: 0;
  height: 100%;
} */
</style>
