<template>
  <div class="news">
    <div>
      <video autoplay muted loop id="myVideo">
        <source src="../assets/network03.mp4" type="video/mp4" />
      </video>
      <div>
        <el-carousel :interval="7000" arrow="always">
          <el-carousel-item v-for="item in 1" :key="item">
            <h3>{{ item }}</h3>
            <img class="item__image" src="../assets/news01.png" alt="" />
          </el-carousel-item>
          <el-carousel-item v-for="item in 1" :key="item">
            <h3>{{ item }}</h3>
            <img class="item__image" src="../assets/news02.png" alt="" />
          </el-carousel-item>
          <el-carousel-item v-for="item in 1" :key="item">
            <h3>{{ item }}</h3>
            <img class="item__image" src="../assets/news03.png" alt="" />
          </el-carousel-item>
          <el-carousel-item v-for="item in 1" :key="item">
            <h3>{{ item }}</h3>
            <img class="item__image" src="../assets/news04.png" alt="" />
          </el-carousel-item>
          <el-carousel-item v-for="item in 1" :key="item">
            <h3>{{ item }}</h3>
            <img class="item__image" src="../assets/news05.png" alt="" />
          </el-carousel-item>
        </el-carousel>
      </div>
    </div></div
></template>
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
</style>
