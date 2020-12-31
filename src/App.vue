<template>
  <div id="app">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div> -->
    <ul>
      <li><router-link id="nav" to="/">Home</router-link></li>
      <li><router-link id="nav" to="/about">About</router-link></li>
      <li><router-link id="nav" to="/news">News</router-link></li>
      <li><router-link id="nav" to="/teachers">Teachers</router-link></li>
      <li><router-link id="nav" to="/artwork">Artwork</router-link></li>

      <!-- <li><a href="#">tags</a></li> -->
    </ul>

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
