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

ul {
  display: flex;
  flex-direction: column;
  align-items: start;
  list-style-type: none;

  li {
    padding: 6px 0;

    a {
      --fill-color: #a7b3bd;
      position: relative;
      display: block;
      padding: 4px 0;
      font: 700 3rem Raleway, sans-serif;
      text-decoration: none;
      text-transform: uppercase;
      -webkit-text-stroke: 2px var(--fill-color);
      background: linear-gradient(var(--fill-color) 0 100%) left / 0 no-repeat;
      color: transparent;
      background-clip: text;
      transition: 0.5s linear;

      &:hover {
        background-size: 100%;
      }
    }
  }
}
</style>
