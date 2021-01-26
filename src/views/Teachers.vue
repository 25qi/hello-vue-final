<template>
  <div class="teachers">
    <div>
      <video autoplay muted loop id="myVideo">
        <source src="../assets/network03.mp4" type="video/mp4" />
      </video>
      <el-row :gutter="20">
        <el-col :span="6"
          ><div class="grid-content bg-purple">
            <div class="flip-card">
              <div class="flip-card-inner">
                <div class="flip-card-front">
                  <img
                    src="../assets/Chiu.jpg"
                    alt="Avatar"
                    style="width:300px;height:300px;"
                  />
                </div>
                <div class="flip-card-back">
                  <h1>邱誌勇</h1>
                  <h3>(Chih-Yung Chiu)</h3>
                  <p>博士/教授</p>
                  <p>
                    專長：新媒體藝術美學、藝術評論、電影電視美學與科技文化研究
                  </p>
                </div>
              </div>
            </div>
          </div></el-col
        >
        <el-col :span="6"
          ><div class="grid-content bg-purple">
            <div class="flip-card">
              <div class="flip-card-inner">
                <div class="flip-card-front">
                  <img
                    src="../assets/Shih.jpg"
                    alt="Avatar"
                    style="width:300px;height:300px;"
                  />
                </div>
                <div class="flip-card-back">
                  <h1>盂施甫</h1>
                  <h3>(Shih-Fu Yu)</h3>
                  <p>講師/新媒體藝術家</p>
                  <p>專長：動力藝術、技術美學、數位製造</p>
                </div>
              </div>
            </div>
          </div></el-col
        >
        <el-col :span="6"
          ><div class="grid-content bg-purple">
            <div class="flip-card">
              <div class="flip-card-inner">
                <div class="flip-card-front">
                  <img
                    src="../assets/Tao.png"
                    alt="Avatar"
                    style="width:300px;height:300px;"
                  />
                </div>
                <div class="flip-card-back">
                  <h1>陶亞倫</h1>
                  <h3>(Tao)</h3>
                  <p>教授/藝術家</p>
                  <p>專長 超媒體藝術 、科技藝術、當代美學</p>
                </div>
              </div>
            </div>
          </div></el-col
        >
        <el-col :span="6"
          ><div class="grid-content bg-purple">
            <div class="flip-card">
              <div class="flip-card-inner">
                <div class="flip-card-front">
                  <img
                    src="../assets/Tsai.jpg"
                    alt="Avatar"
                    style="width:300px;height:300px;"
                  />
                </div>
                <div class="flip-card-back">
                  <h1>蔡奇宏</h1>
                  <h3>(Chi-Hung Tsai)</h3>
                  <p>講師/科技藝術業界顧問教師</p>
                  <p>專長：光動藝術、互動裝置藝術、策展規劃與執行</p>
                </div>
              </div>
            </div>
          </div></el-col
        >
      </el-row>
    </div>
  </div></template
>
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
.flip-card {
  background-color: transparent;
  width: 300px;
  height: 300px;
  border: 1px solid #969393;
  perspective: 1000px; /* Remove this if you don't want the 3D effect */
}

/* This container is needed to position the front and back side */
.flip-card-inner {
  position: relative;
  width: 100%;
  height: 100%;
  text-align: center;
  transition: transform 0.8s;
  transform-style: preserve-3d;
}

/* Do an horizontal flip when you move the mouse over the flip box container */
.flip-card:hover .flip-card-inner {
  transform: rotateY(180deg);
}

/* Position the front and back side */
.flip-card-front,
.flip-card-back {
  position: absolute;
  width: 100%;
  height: 100%;
  -webkit-backface-visibility: hidden; /* Safari */
  backface-visibility: hidden;
}

/* Style the front side (fallback if image is missing) */
.flip-card-front {
  background-color: rgb(44, 43, 43);
  color: black;
}

/* Style the back side */
.flip-card-back {
  background-color: rgba(51, 53, 54, 0);
  color: rgb(227, 231, 233);
  transform: rotateY(180deg);
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
  background-color: rgba(000, 000, 000, 0);
}
.bg-purple {
  background-color: rgba(000, 000, 000, 0);
}
.bg-purple-light {
  background-color: rgba(000, 000, 000, 0);
}
.grid-content {
  border-radius: 4px;
  min-height: 36px;
}
.row-bg {
  padding: 10px 0;
  background-color: rgba(000, 000, 000, 0);
}
</style>
