<template>
  <div class="about">
    <div>
<<<<<<< HEAD
=======
      <hr align="left" width="200%" />
      <h1 style="color:white;">實驗性頁面(建議從左手邊出去)</h1>
      <p style="color:white;">
        國立清華大學藝術學院學士班
        30014新竹市南大路521號（教學大樓3F）+886-3-5715131 #78802 /
        ipta@my.nthu.edu.tw
      </p>
      <!-- <video width="320" height="240" src="../assets/Comp01.mov"></video> -->
    </div>
    <div>
>>>>>>> 3dad63010fceae0106aae6b92e2aebfe085cba0d
      <video autoplay muted loop id="myVideo">
        <source src="../assets/network03.mp4" type="video/mp4" />
      </video>
    </div>
<<<<<<< HEAD
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
=======
    <el-carousel :interval="4000" type="card" height="300px">
      <el-carousel-item>
        <div class="item">
          <div class="item__content">
            Text for slide 1
          </div>
          <img
            class="item__image"
            src="https://picsum.photos/300?random=1"
            alt=""
          />
        </div>
      </el-carousel-item>
      <el-carousel-item>
        <div class="item">
          <div class="item__content">
            Another text for slide 2
          </div>
          <img
            class="item__image"
            src="https://picsum.photos/300?random=2"
            alt=""
          />
        </div>
      </el-carousel-item>
      <el-carousel-item>
        <div class="item">
          <div class="item__content">
            Yet another for third image
          </div>
          <img
            class="item__image"
            src="https://picsum.photos/300?random=3"
            alt=""
          />
        </div>
      </el-carousel-item>
    </el-carousel>
    <el-carousel :interval="4000" type="card" height="300px">
      <el-carousel-item>
        <div class="item">
          <div class="item__content">
            Text for slide 1
          </div>
          <img
            class="item__image"
            src="https://picsum.photos/300?random=1"
            alt=""
          />
        </div>
      </el-carousel-item>
      <el-carousel-item>
        <div class="item">
          <div class="item__content">
            Another text for slide 2
          </div>
          <img
            class="item__image"
            src="https://picsum.photos/300?random=2"
            alt=""
          />
        </div>
      </el-carousel-item>
      <el-carousel-item>
        <div class="item">
          <div class="item__content">
            Yet another for third image
          </div>
          <img
            class="item__image"
            src="https://picsum.photos/300?random=3"
            alt=""
          />
        </div>
      </el-carousel-item>
    </el-carousel>
>>>>>>> 3dad63010fceae0106aae6b92e2aebfe085cba0d
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
<<<<<<< HEAD
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
=======

  @import url("https://fonts.googleapis.com/css?family=Raleway:400,400i,700");

  // body {
  //   display: flex;
  //   height: 100vh;
  //   justify-content: left;
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

  @import url(https://fonts.googleapis.com/css?family=Roboto:400);
  @import url(https://maxcdn.bootstrapcdn.com/font-awesome/4.5.0/css/font-awesome.min.css);
  *,
  *:before,
  *:after {
    box-sizing: border-box;
  }

  html,
  body {
    height: 100%;
  }

  body {
    color: #444;
    font-family: "Roboto", sans-serif;
    font-size: 1rem;
    line-height: 1.5;
  }

  .slider {
    height: 100%;
    position: relative;
    overflow: hidden;
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-flex-flow: row nowrap;
    -ms-flex-flow: row nowrap;
    flex-flow: row nowrap;
    -webkit-box-align: end;
    -webkit-align-items: flex-end;
    -ms-flex-align: end;
    align-items: flex-end;
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
  }
  .slider__nav {
    width: 12px;
    height: 12px;
    margin: 2rem 12px;
    border-radius: 50%;
    z-index: 10;
    outline: 6px solid #ccc;
    outline-offset: -6px;
    box-shadow: 0 0 0 0 #333, 0 0 0 0 rgba(51, 51, 51, 0);
    cursor: pointer;
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    -webkit-backface-visibility: hidden;
    backface-visibility: hidden;
  }
  .slider__nav:checked {
    -webkit-animation: check 0.4s linear forwards;
    animation: check 0.4s linear forwards;
  }
  .slider__nav:checked:nth-of-type(1) ~ .slider__inner {
    left: 0%;
  }
  .slider__nav:checked:nth-of-type(2) ~ .slider__inner {
    left: -100%;
  }
  .slider__nav:checked:nth-of-type(3) ~ .slider__inner {
    left: -200%;
  }
  .slider__nav:checked:nth-of-type(4) ~ .slider__inner {
    left: -300%;
  }
  .slider__inner {
    position: absolute;
    top: 0;
    left: 0;
    width: 400%;
    height: 100%;
    -webkit-transition: left 0.4s;
    transition: left 0.4s;
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-flex-flow: row nowrap;
    -ms-flex-flow: row nowrap;
    flex-flow: row nowrap;
  }
  .slider__contents {
    height: 100%;
    padding: 2rem;
    text-align: center;
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-flex: 1;
    -webkit-flex: 1;
    -ms-flex: 1;
    flex: 1;
    -webkit-flex-flow: column nowrap;
    -ms-flex-flow: column nowrap;
    flex-flow: column nowrap;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
  }
  .slider__image {
    font-size: 2.7rem;
    color: #2196f3;
  }
  .slider__caption {
    font-weight: 500;
    margin: 2rem 0 1rem;
    text-shadow: 0 1px 1px rgba(0, 0, 0, 0.1);
    text-transform: uppercase;
  }
  .slider__txt {
    color: #999;
    margin-bottom: 3rem;
    max-width: 300px;
  }

  @-webkit-keyframes check {
    50% {
      outline-color: #333;
      box-shadow: 0 0 0 12px #333, 0 0 0 36px rgba(51, 51, 51, 0.2);
    }
    100% {
      outline-color: #333;
      box-shadow: 0 0 0 0 #333, 0 0 0 0 rgba(51, 51, 51, 0);
    }
  }

  @keyframes check {
    50% {
      outline-color: #333;
      box-shadow: 0 0 0 12px #333, 0 0 0 36px rgba(51, 51, 51, 0.2);
    }
    100% {
      outline-color: #333;
      box-shadow: 0 0 0 0 #333, 0 0 0 0 rgba(51, 51, 51, 0);
    }
  }
}
.el-row {
  margin-bottom: 20px;
  &:last-child {
    margin-bottom: 0;
  }
}
.el-col {
  border-radius: 4px;
}
.bg-purple-dark {
  background: #99a9bf;
}
.bg-purple {
  background: #d3dce6;
}
.bg-purple-light {
  background: #e5e9f2;
}
.grid-content {
  border-radius: 4px;
  min-height: 36px;
}
.row-bg {
  padding: 10px 0;
  background-color: #f9fafc;
}
</style>

<script>
export default {
  data() {
    return {};
  },
};
</script>
>>>>>>> 3dad63010fceae0106aae6b92e2aebfe085cba0d
