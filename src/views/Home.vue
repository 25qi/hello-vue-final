<template>
  <div class="home">
    <!-- <div class="logo"><img alt="Vue logo" src="../assets/logo.png" /></div> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
    <!-- <ul>
      <li><a href="#">home</a></li>
      <li><a href="#" router-link to="/about">archives</a></li>
      <li><a href="#">tags</a></li>
      <li><a href="#">categories</a></li>
      <li><a href="#">about</a></li>
    </ul> -->
    <!-- The video -->
    <video autoplay muted loop id="myVideo">
      <source src="../assets/network03.mp4" type="video/mp4" />
    </video>
  </div>
</template>
<style></style>
//
<script>
// // @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

// export default {
//   name: 'Home',
//   components: {
//     HelloWorld
//   }
// }
//
</script>

<style lang="scss">
#myVideo {
  position: fixed;
  margin: 0px;
  right: 0;
  left: 0px;
  bottom: 0;
  top: 0;
  min-width: 100%;
  min-height: 100%;
  z-index: -999;
}
// https://picular.co/bluemoon

@import url("https://fonts.googleapis.com/css?family=Raleway:400,400i,700");

// body {
//   display: flex;
//   height: 100vh;
//   justify-content: center;
//   align-items: stretch;
//   text-align: center;
//   background: #171617;
// }

body,
html {
  margin: 0;
  padding: 0;
  height: 100%;
  z-index: 99;
}
body {
  background: rbga(0, 0, 0, 0);
  // box-shadow: inset 0 0 20vmin 0 #ffffff;
}
.wrap {
  position: relative;
  width: 80vmin;
  height: 80vmin;
  margin: 0 auto;
  background: inherit;
  transform: scale(0.2) translatez(0px);
  opacity: 0;
  transition: transform 0.5s, opacity 0.5s;
}
.nav_circle {
  position: absolute;
  left: 0;
  top: 0;
  width: 47.5%;
  height: 47.5%;
  overflow: hidden;
  transform: scale(0.5) translateZ(0px);
  background: #585247;
}
.nav_circle .nav_circle02 {
  height: 100%;
  background-size: cover;
  opacity: 0.5;
  transition: opacity 0.5s;
  border-radius: inherit;
}
.nav_circle:nth-child(1) {
  border-radius: 40vmin 0 0 0;
  transform-origin: 110% 110%;
  transition: transform 0.4s 0.15s;
}
.nav_circle:nth-child(1) .nav_circle02 {
  background-image: url("../assets/mirror.png");
}
.nav_circle:nth-child(2) {
  border-radius: 0 40vmin 0 0;
  left: 52.5%;
  transform-origin: -10% 110%;
  transition: transform 0.4s 0.2s;
}
.nav_circle:nth-child(2) .nav_circle02 {
  background-image: url("../assets/mycamera.png");
}
.nav_circle:nth-child(3) {
  border-radius: 0 0 0 40vmin;
  top: 52.5%;
  transform-origin: 110% -10%;
  transition: transform 0.4s 0.25s;
}
.nav_circle:nth-child(3) .nav_circle02 {
  background-image: url("../assets/video05.jpg");
}
.nav_circle:nth-child(4) {
  border-radius: 0 0 40vmin 0;
  top: 52.5%;
  left: 52.5%;
  transform-origin: -10% -10%;
  transition: transform 0.4s 0.3s;
}
.nav_circle:nth-child(4) .nav_circle02 {
  background-image: url("../assets/myself02.jpg");
}
.nav_circle:nth-child(5) {
  width: 55%;
  height: 55%;
  left: 22.5%;
  top: 22.5%;
  border-radius: 50vmin;
  box-shadow: 0 0 0 5vmin rgba(0, 0, 0, 0.8);
  transform: scale(1);
}
.nav_circle:nth-child(5) .nav_circle02 {
  background-image: url("../assets/myself.jpg");
}
.circle_span {
  position: relative;
  display: block;
  margin: 0 auto;
  top: 45vmin;
  width: 10vmin;
  height: 10vmin;
  border-radius: 100%;
  background: #585247;
  transform: translateZ(0px);
}
.circle_span span {
  position: absolute;
  width: 60%;
  height: 3px;
  background: #aca696;
  left: 20%;
  top: 50%;
  border-radius: 0;
}
.circle_span span:after,
.circle_span span:before {
  content: "";
  position: absolute;
  left: 0;
  top: -1.5vmin;
  width: 100%;
  height: 100%;
  background: inherit;
}
.circle_span span:after {
  top: 1.5vmin;
}
.circle_span:hover + .wrap,
.wrap:hover {
  transform: scale(0.8) translateZ(0px);
  opacity: 1;
}
.circle_span:hover + .wrap .nav_circle,
.wrap:hover a {
  transform: scale(1) translatez(0px);
}
.nav_circle:hover .nav_circle02 {
  opacity: 1;
  transform: translatez(0px);
}
</style>
