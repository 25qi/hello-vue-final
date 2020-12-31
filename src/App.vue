<template>
  <div id="app">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div> -->
    <span class="circle_span"><span></span></span>
    <div class="wrap">
      <a href="#" class="nav_circle"
        ><router-link id="nav" to="/page_mirror"></router-link>
        <div class="nav_circle02"></div
      ></a>
      <a href="#" class="nav_circle"
        ><router-link id="nav" to="/about"></router-link>
        <div class="nav_circle02"></div
      ></a>
      <a href="#" class="nav_circle"
        ><router-link id="nav" to="/page_video"></router-link>
        <div class="nav_circle02"></div
      ></a>
      <a href="#" class="nav_circle"
        ><router-link id="nav" to="/page_myself"></router-link>
        <div class="nav_circle02"></div
      ></a>
      <a href="#" class="nav_circle"
        ><router-link id="nav" to="/"></router-link>
        <div class="nav_circle02"></div
      ></a>
    </div>

    <router-view />
  </div>
</template>

<style lang="scss">
// #app {
//   font-family: Avenir, Helvetica, Arial, sans-serif;
//   -webkit-font-smoothing: antialiased;
//   -moz-osx-font-smoothing: grayscale;
//   text-align: center;
//   color: #2c3e50;
// }

// #nav {
//   padding: 30px;

//   a {
//     font-weight: bold;
//     color: #2c3e50;

//     &.router-link-exact-active {
//       color: #42b983;
//     }
//   }
// }
//
</style>
