<template>
  <div class="artwork">
    <div>
      <video autoplay muted loop id="myVideo">
        <source src="../assets/network03.mp4" type="video/mp4" />
      </video>
    </div>
    <el-carousel :interval="4000" type="card" height="700px">
      <el-carousel-item v-for="item in 1" :key="item">
        <h3 class="medium">{{ item }}</h3>
        <img class="item__image" src="../assets/001.jpg" alt="" />
      </el-carousel-item>
      <el-carousel-item v-for="item in 1" :key="item">
        <h3 class="medium">{{ item }}</h3>
        <img class="item__image" src="../assets/002.jpg" alt="" />
      </el-carousel-item>
      <el-carousel-item v-for="item in 1" :key="item">
        <h3 class="medium">{{ item }}</h3>
        <img class="item__image" src="../assets/003.jpg" alt="" />
      </el-carousel-item>
      <el-carousel-item v-for="item in 1" :key="item">
        <h3 class="medium">{{ item }}</h3>
        <img class="item__image" src="../assets/004.jpg" alt="" />
      </el-carousel-item>
    </el-carousel></div
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
.el-carousel__item h3 {
  color: rgb(0, 0, 0);
  font-size: 14px;
  opacity: 0.75;
  line-height: 200px;
  margin: 0;
}

.el-carousel__item:nth-child(2n) {
  background-color: rgba(44, 43, 43, 0);
}

.el-carousel__item:nth-child(2n + 1) {
  background-color: rgba(44, 43, 43, 0);
}
</style>
