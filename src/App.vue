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
  background: #ff0000;
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
  transform-origin: 100%;
  transform: skewY(-4deg);
}
body, html {
  margin: 0;
  height: 100%;
} */
</style>
