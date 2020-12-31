<template>
  <div class="page_mirror">
    <div>
      <video autoplay muted loop id="myVideo">
        <source src="../assets/network03.mp4" type="video/mp4" />
      </video>
    </div>
    <div style="height:500px;position:relative;"></div>
    <div>
      <el-carousel :interval="4000" type="card" height="450px">
        <el-carousel-item v-for="item in 1" :key="item">
          <h3 class="medium">{{ item }}</h3>
          <img class="item__image" src="../assets/mirror01.png" alt="" />
        </el-carousel-item>
        <el-carousel-item v-for="item in 1" :key="item">
          <h3 class="medium">{{ item }}</h3>
          <img class="item__image" src="../assets/mirror02.png" alt="" />
        </el-carousel-item>
        <el-carousel-item v-for="item in 1" :key="item">
          <h3 class="medium">{{ item }}</h3>
          <img class="item__image" src="../assets/mirror03.png" alt="" />
        </el-carousel-item>
        <el-carousel-item v-for="item in 1" :key="item">
          <h3 class="medium">{{ item }}</h3>
          <img class="item__image" src="../assets/mirror04.png" alt="" />
        </el-carousel-item>
      </el-carousel>
    </div>
    <div style="height=500px;position:relative;"></div>
    <div class="card">
      <div class="right">
        <h1>Mr.Bacteria 鏡觀微物</h1>
        <hr />

        <a href="https://youtu.be/9sC4fo4M2kg" target="_blank"
          ><p>作品影片連結</p></a
        >

        <h2>作品簡介</h2>
        <p>
          我們的作品呈現概念非常簡單，就是在鏡子上面培養菌種和微生物，用拍照的方式記錄鏡面上片的變化，用影片的方式記錄那些鏡子的所在環境。
          總共使用四個鏡面，希望觀者能自行前往觀展(似尋寶過程)
        </p>
        <ul>
          <li>
            9306教室的櫃子裡:是我們幾乎每天會開關的地方，捕捉到的微生物來自櫃子內部或開關櫃子的人們。
          </li>
          <li>
            系上工廠(9304):是我們班上最常活動的地方，這片鏡子應紀錄著系上同學、木料或壓克力的各種粉塵之微生物。
          </li>
          <li>
            戶外(系上大樓後方草地)
          </li>
          <li>
            帶著走:我或是共同創作者方晨軒隨身帶著的鏡子，因此鏡面會捕捉我們到過的每個地方。對我而言，因為這件作品我會比平常更細心關注我當下走過的環境，而非只是目的性的，為了吃飯、為了回宿舍、為了去上課，而走過那些地方。那麼一想到鏡子捕捉了每個當下，便覺莫名興奮。
          </li>
          <li>
            我自認為觀者不必要聯想到以上我想傳達的創作理念或連結到某些議題，一般大眾也可以用一個鏡子上面長了有趣漂亮的東西來看待，而我自己也覺得拍攝這些作品的過程是有趣的，可以拍到自己在拍攝這件作品的樣子，以及每次拍攝呈現的微生物的那些無法預期的不規則生長之美。
          </li>
        </ul>
        <h2>創作理念與作品意義</h2>
        <ul>
          <li>
            我期待的真實的展覽呈現方式是，觀者觀賞的是一個過程，而非鏡面呈現結果。觀者能隔幾天或幾小時去觀看這件作品，觀察鏡面呈現的不同變化，如同這些維生物與菌類就是與你一同存在與生長一般，就是這件作品的變化軌跡以及生存證明。
          </li>
          <li>
            透過讓菌種變成肉眼可關注的對象，並且在鏡面上的呈現，讓觀者同時可關注到自己以及鏡面上的有著在這個環境下存在的微生物，有同在之感
          </li>
          <li>
            鏡子幾乎是日常生活的必需品，人每天都要照鏡子，並且會在鏡子前停留一些時間，因此我希望營造一個很日常的行為來觀賞這件作品，就像你平常照鏡子一般，經過鏡子便會"順手"瞧一眼鏡子，而這時候你又會發現這個鏡面有些許不同
          </li>
          <li>
            我在最後的生物期末發表時，是以影片呈現的方式，除了鏡面本身的微生物變化，也同時紀錄著鏡子的看過去的角度及捕捉到的環境世界，這跟純粹用攝影機捕捉當下是不一樣的，因為那個影像只是存在視網膜的虛像環境，鏡面捕捉到的是真實的環境(中的微生物)。但為了方便呈現我帶著鏡子走過的旅程，我仍用攝影機紀錄著，但觀者可把影片想像成那就是鏡面捕捉到的世界，只是我用一個媒介(攝影機的視角)將他變成觀者的角度容易理解的呈現方式。
          </li>
          <li>
            我自認為觀者不必要聯想到以上我想傳達的創作理念或連結到某些議題，一般大眾也可以用一個鏡子上面長了有趣漂亮的東西來看待，而我自己也覺得拍攝這些作品的過程是有趣的，可以拍到自己在拍攝這件作品的樣子，以及每次拍攝呈現的微生物的那些無法預期的不規則生長之美。
          </li>
        </ul>
      </div>
    </div>
    <div style="height:200px;position:relative;"></div></div
></template>
<style lang="scss">
.el-carousel__item h3 {
  color: rgba(0, 0, 0, 0);
  font-size: 14px;
  opacity: 0;
  line-height: 0px;
  margin: 0;
}

.el-carousel__item:nth-child(2n) {
  background-color: rgba(255, 255, 255, 0);
}

.el-carousel__item:nth-child(2n + 1) {
  background-color: rgba(255, 255, 255, 0);
}
.card {
  width: 1000px;
  display: flex;
  color: white;
  margin: auto;
  line-height: 30px;
}
/* .left,.right{
  border-color: red;
} */

.right {
  width: 100%;
}
ul li {
  display: auto;
}
</style>
