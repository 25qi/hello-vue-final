<template>
  <div class="page_video">
    <div>
      <video autoplay muted loop id="myVideo">
        <source src="../assets/network03.mp4" type="video/mp4" />
      </video>
    </div>
    <div style="height:300px;position:relative;"></div>
    <h1
      style="z-index: 1000;
  color:white;
  text-align: center;"
    >
      2020影片成果
    </h1>
    <div style="height:100px;position:relative;"></div>
    <section>
      <img src="../assets/video02.jpg" alt="" />
      <a href="https://youtu.be/bwLfaCNAju0" target="_blank">
        <article>
          <div></div>
          <div></div>
          <div></div>
          <div></div>
          <div></div>
        </article>
      </a>
    </section>
    <div style="height:100px;position:relative;"></div>
    <section>
      <img src="../assets/video05.jpg" alt="" />
      <a href="https://youtu.be/P3coMRcsboI" target="_blank">
        <article>
          <div></div>
          <div></div>
          <div></div>
          <div></div>
          <div></div>
        </article>
      </a>
    </section>
    <div style="height:100px;position:relative;"></div>
    <section class="section2">
      <img src="../assets/video04.jpg" alt="" />
      <a href="https://youtu.be/NUjBN6WJpaI" target="_blank">
        <article>
          <div></div>
          <div></div>
          <div></div>
          <div></div>
          <div></div>
        </article>
      </a>
    </section>
    <div style="height:100px;position:relative;"></div>
    <section>
      <img src="../assets/video03.jpg" alt="" />
      <a href="https://youtu.be/JX8dkp8QHWA" target="_blank">
        <article>
          <div></div>
          <div></div>
          <div></div>
          <div></div>
          <div></div>
        </article>
      </a>
    </section>
    <div style="height:100px;position:relative;"></div>
    <section class="section2">
      <img src="../assets/video01.jpg" alt="" />

      <a href="https://youtu.be/Bgglb8kHAQM" target="_blank">
        <article>
          <div></div>
          <div></div>
          <div></div>
          <div></div>
          <div></div>
        </article>
      </a>
    </section>
    <div style="height:200px;position:relative;"></div></div
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

section {
  width: 80%;
  margin: 0 auto;
  line-height: 0;
  position: relative;
}
section img {
  width: 100%;
}
section article {
  position: absolute;
  top: 0;
  width: 100%;
  background: rgba(0, 0, 0, 0.8);
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-gap: 20px;
  mix-blend-mode: multiply;
}
section div {
  background: rgb(255, 255, 255);
  height: 19.7vw;
}
section div:nth-of-type(2) {
  grid-column: 2 / 4;
}

.section2 article {
  position: absolute;
  top: 0;
  width: 100%;
  background: rgba(0, 0, 0, 0.8);
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-gap: 20px;
  mix-blend-mode: darken;
}
.section2 div {
  background: rgb(255, 255, 255);
  height: 20.7vw;
}
</style>
