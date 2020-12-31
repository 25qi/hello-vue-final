<template>
  <div class="about">
    <div>
      <video autoplay muted loop id="myVideo">
        <source src="../assets/network03.mp4" type="video/mp4" />
      </video>
    </div>
    <div class="resume">
      <div class="top">
        <div class="infos">
          <h1 class="name">
            黃琦 <span><span>QI,Huang</span></span>
          </h1>
          <br />
          <h1 class="job">Artist</h1>
          <div class="icons">
            <a
              href="https://www.facebook.com/profile.php?id=100004750651648"
              target="_blank"
              ><img
                src="https://www.flaticon.com/svg/vstatic/svg/1384/1384005.svg?token=exp=1611680824~hmac=126fbd6469b59688ff79a057438adc99"
                alt=""/></a
            ><a href="https://www.instagram.com/25qi_/" target="_blank"
              ><img
                src="https://www.flaticon.com/svg/vstatic/svg/1384/1384015.svg?token=exp=1611681031~hmac=a20b6023f3703e5a22946a3ea75a2982"
                alt=""
            /></a>
            <a
              href="https://www.youtube.com/channel/UCnPUdy5OVDr6CL61P-JM99A"
              target="_blank"
              ><img
                src="https://www.flaticon.com/svg/vstatic/svg/1384/1384012.svg?token=exp=1611681225~hmac=942a2f7444c84d1cfd62989ac530fc69"
                alt=""
            /></a>
            <a href="https://github.com/25qi" target="_blank"
              ><img
                src="https://www.flaticon.com/svg/vstatic/svg/2111/2111425.svg?token=exp=1611678443~hmac=6fb03703b6168757d4760ec55d4daf52"
                alt=""
            /></a>
          </div>
        </div>
        <img class="profile" src="../assets/mycamera.png" alt="" />
        <article class="gradient"></article>
      </div>

      <div class="bottom">
        <h2 class="title2">2020技能分析</h2>
        <div class="techs1">
          <div class="tech tech1-1">
            <div class="circle">
              <div class="square"></div>
              <div class="square1"></div>
              <div class="square1-1"></div>
              <div class="scircle"></div>
            </div>
            <h2 class="text">UI design</h2>
          </div>
          <div class="tech tech1-2">
            <div class="circle">
              <div class="square"></div>
              <div class="square1"></div>
              <div class="square1-1"></div>
              <div class="square2"></div>
              <div class="scircle"></div>
            </div>
            <h2 class="text">Video Edit 剪輯</h2>
          </div>
          <div class="tech tech1-3">
            <div class="circle">
              <div class="square"></div>
              <div class="square1"></div>
              <div class="square1-1"></div>
              <div class="scircle"></div>
            </div>
            <h2 class="text">Motion Graphic</h2>
          </div>
        </div>
        <div class="techs2">
          <div class="tech tech2-1">
            <div class="circle">
              <div class="square"></div>
              <div class="square1"></div>
              <div class="scircle"></div>
            </div>
            <h2 class="text">Maker 自造者</h2>
          </div>
          <div class="tech tech2-2">
            <div class="circle">
              <div class="square"></div>
              <div class="square1"></div>
              <div class="scircle"></div>
            </div>
            <h2 class="text">3D design</h2>
          </div>
          <div class="tech tech2-3">
            <div class="circle">
              <div class="square square6"></div>
              <div class="scircle"></div>
            </div>
            <div class="text">Front end 前端</div>
          </div>
        </div>
      </div>
      <div class="bottom2">
        <h2 class="title2">2020程式語言分析</h2>
        <div class="part">
          <div class="content">HTML</div>
          <div class="bar">
            <div class="progress1"></div>
          </div>
        </div>
        <div class="part">
          <div class="content">CSS</div>
          <div class="bar">
            <div class="progress2"></div>
          </div>
        </div>
        <div class="part">
          <div class="content">Javascript</div>
          <div class="bar">
            <div class="progress3"></div>
          </div>
        </div>
        <div class="part">
          <div class="content">C/C++</div>
          <div class="bar">
            <div class="progress4"></div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
#myVideo {
  position: fixed;
  margin: 0px;
  right: 0;
  left: 0;
  bottom: 0;
  top: 0;
  min-width: 100%;
  min-height: 100%;
  z-index: -999;
}

* {
  font-family: 微軟正黑體;
}

body {
  padding: 10px;
  background-color: #e0f4ff;
}

.resume {
  padding: 50px;
}

.top {
  border-radius: 20px 20px 0px 0px;
  padding: 50px;
  background: radial-gradient(
    circle,
    rgba(255, 255, 255, 0.6),
    rgba(0, 0, 0, 0)
  );
  display: flex;
  position: relative;
  color: white;
}
// .top .gradient {
//   position: absolute;
//   top: 0;
//   width: 100%;
//   background: radial-gradient(
//     circle,
//     rgba(255, 255, 255, 0.6),
//     rgba(0, 0, 0, 0)
//   );
//   display: grid;
//   grid-template-columns: 1fr 1fr 1fr;
//   grid-gap: 20px;
//   mix-blend-mode: multiply;
// }
.top .profile {
  width: 40%;
  height: 40%;
  flex: 7;
  border-radius: 20px 20px 20px 20px;
}
.top .infos {
  flex: 5;
  align-items: flex-end;
}
.top .infos .name {
  margin-top: 100px;
  font-weight: 400;
}
.top .infos .name span {
  font-size: 18px;
}
.top .infos .job {
  margin-top: -10px;
  margin-left: 5px;
}
.top .infos .icons {
  bottom: 30px;
  box-shadow: 0px 1px 30px #ababab;
  padding: 15px 30px;
  position: absolute;
  width: 400px;
  margin-left: -150px;
  text-align: right;
  border-radius: 0px 50px 50px 0px;
}
.top .infos .icons img {
  margin-right: 30px;
  width: 50px;
  height: 50px;
}

.bottom {
  padding: 20px 60px 40px 60px;
  background: radial-gradient(
    circle,
    rgba(150, 150, 150, 0.8),
    rgba(0, 0, 0, 0)
  );
  color: rgba(255, 255, 255, 1);
}
.bottom .title2 {
  margin-bottom: 20px;
  text-align: center;
  position: relative;

  transform: translateX(-30px);
}

.techs1,
.techs2 {
  margin-top: 50px;
  display: flex;
  justify-content: space-around;
}
.techs1 .tech,
.techs2 .tech {
  text-align: center;
  position: relative;
  width: 200px;
}
.techs1 .tech .text,
.techs2 .tech .text {
  margin-top: 30px;
  font-size: 18px;
  font-weight: 400;
}
.techs1 .tech .circle,
.techs2 .tech .circle {
  left: 50%;
  transform: translate(-50%);
  width: 80px;
  height: 80px;
  border-radius: 50%;
  background-color: rgba(255, 255, 255, 0.15);
  position: relative;
  overflow: hidden;
}
.techs1 .tech .circle .square,
.techs2 .tech .circle .square {
  width: 40px;
  height: 40px;
  background-color: rgba(255, 255, 255, 0.7);
  position: absolute;
  left: 50%;
}
.techs1 .tech .circle .square1,
.techs2 .tech .circle .square1 {
  width: 40px;
  height: 40px;
  background-color: rgba(255, 255, 255, 0.7);
  position: absolute;
  left: 50%;
  top: 50%;
}
.techs1 .tech .circle .square2,
.techs2 .tech .circle .square2 {
  width: 40px;
  height: 40px;
  background-color: rgba(255, 255, 255, 0.7);
  position: absolute;
}
.techs1 .tech .circle .square1-1,
.techs2 .tech .circle .square1-1 {
  width: 40px;
  height: 40px;
  background-color: rgba(255, 255, 255, 0.7);
  position: absolute;
  top: 50%;
}
.techs1 .tech .circle .scircle,
.techs2 .tech .circle .scircle {
  width: 60px;
  height: 60px;
  border-radius: 50%;
  background-color: rgb(55, 54, 55);
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
}

.bottom2 {
  border-radius: 0px 0px 20px 20px;
  box-sizing: border-box;
  padding: 20px 50px 50px 50px;
  width: 100%;
  text-align: center;
  background: radial-gradient(
    circle,
    rgba(255, 255, 255, 0.6),
    rgba(0, 0, 0, 0)
  );
}
.bottom2 .title2 {
  margin-bottom: 50px;
  color: white;
}

.part {
  margin-top: 30px;
  height: 20px;
  box-sizing: border-box;
}
.part .content {
  margin-right: 20px;
  width: 100px;
  text-align: left;
  height: 100%;
  box-sizing: border-box;
  color: rgba(255, 255, 255, 0.7);
}
.part .bar {
  height: 100%;
  width: 800px;
  border: solid 2px rgba(0, 0, 0, 0.5);
  border-radius: 20px;
  box-sizing: border-box;
}
.part .bar .progress1 {
  border: none;
  width: 400px;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.5);
  border-radius: 20px;
}
.part .bar .progress2 {
  border: none;
  width: 400px;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.5);
  border-radius: 20px;
}
.part .bar .progress3 {
  border: none;
  width: 90px;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.5);
  border-radius: 20px;
}
.part .bar .progress4 {
  border: none;
  width: 250px;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.5);
  border-radius: 20px;
}

.bar,
.content {
  display: inline-block;
}
</style>
