<template>
  <div class="about">
    <div>
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
      <video autoplay muted loop id="myVideo">
        <source src="../assets/network03.mp4" type="video/mp4" />
      </video>
    </div>
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
