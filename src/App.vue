<template>
  <div>
    <h1>
      <a
        style="color: #243a73; text-decoration: none"
        href="https://buy.stripe.com/8wMaIe5rGdg23lKaEQ"
        >Toru's crazy Japanese lessons</a
      >
    </h1>
    <div style="margin: 20px 10px">
      <span style="font-size: 30px; color: #243a73">3</span> lessons
      <span style="font-size: 30px; color: #243a73">98</span> $
    </div>
    <p style="margin: 20px 10px">
      Welcome to Toru's crazy Japanese Lessons! <br />
      You will learn Japanese used in Anime and daily conversations step by
      step. The 60 minutes private lessons will be held three times in a month.
      Pls DM me through insta or messenger for a free trial lesson :)
    </p>
  </div>
  <div style="margin: 50px 10px 50px">
    <h1>
      <a
        style="color: #243a73; text-decoration: none"
        href="https://buy.stripe.com/6oE2bI5rGcbY2hGdR4"
        >おとなの英会話教室</a
      >
    </h1>
    <div style="margin: 20px 10px">
      <span style="font-size: 30px; color: #243a73">1</span> レッスン
      <span style="font-size: 30px; color: #243a73">4,800</span> 円
    </div>
    <p style="margin: 20px 10px">
      プライベートで英会話をおしえます。<br />
      1回の授業は60分、レッスンをお申し込みの際はSNSでDMください＾＾
    </p>
  </div>
  <div style="margin: 50px 10px 50px">
    <h1>
      <a
        style="color: #243a73; text-decoration: none"
        href="https://buy.stripe.com/14k7w2f2gcbYaOcdR0"
        >Phone call with Toru</a
      >
    </h1>
    <div style="margin: 20px 10px">
      <span style="font-size: 30px; color: #243a73">20</span> $
      <span style="font-size: 30px; color: #243a73">/</span>
      <span style="font-size: 30px; color: #243a73">3000</span> 円
    </div>
    <p style="margin: 20px 10px">
      20 US dollors for 30min phone call with me :) Pls DM me through insta or
      messenger for more details.<br /><br />
      30分の電話3000円くらい、レッスンをお申し込みの際はSNSでDMください＾＾
    </p>
  </div>
  <div style="margin: 50px 10px 50px">
    <h1>
      <a
        style="color: #243a73; text-decoration: none"
        href="https://buy.stripe.com/cN2aIeg6k0tgcWkeV7"
        >レンタルとーる🍈</a
      >
    </h1>
    <div style="margin: 20px 10px">
      <span style="font-size: 30px; color: #243a73">1</span> 時間
      <span style="font-size: 30px; color: #243a73">4,800</span> 円
    </div>
    <p style="margin: 20px 10px">
      東京都内または横浜周辺でデートしましょう！<br />
      お申し込みの際はSNSでDMください＾＾
    </p>
  </div>
  <div style="margin: 50px 10px 50px">
    <h1 style="border-bottom: 3px solid yellow">
      <a style="color: #243a73; text-decoration: none">subscription</a>
    </h1>
    <div style="margin: 20px 10px">
      <span style="font-size: 30px; color: #243a73">10</span> $
      <span style="font-size: 30px; color: #243a73">/</span>
      <span style="font-size: 30px; color: #243a73">1470</span> 円
    </div>
    <p style="margin: 20px 10px">
      We will have subscription only live after normal live several times a
      week. <br />
      You are free to come up to small window and talk with Toru and make
      friends!<br /><br />
      普通のライブ配信の後、週に数回サブスク限定配信をします。
      サブスク配信では小窓に自由に上がっていただけます。
      僕や外国人の視聴者さんなどと一緒にお話をしてお友達を作りましょう！
    </p>
  </div>
  <div style="margin: 50px 10px 80px">
    <h1 style="border-bottom: 3px solid yellow">
      <a style="color: #243a73; text-decoration: none">merchandise / グッズ</a>
    </h1>
    <div style="margin: 20px 10px">
      <span style="font-size: 30px; color: #243a73">30</span> $
      <span style="font-size: 30px; color: #243a73">/</span>
      <span style="font-size: 30px; color: #243a73">3000</span> 円
    </div>
    <p style="margin: 20px 10px 0">
      I will send you a original postcard with pictures and messages. Also,
      there will be a keyfolder. Please choose one from below and DM me when you
      order.<br /><br />
      ライブをいつも見てくれている人限定で写真とオリジナルメッセージ付きのポストカードをお送りします。
      合わせて、キーホルダーも以下の4種類から1つお送りします。お申し込みの際はDMください＾＾<br /><br />
    </p>
    <div class="flex-box">
      <div class="carousel">
        <div
          class="carousel-inner"
          :style="{ transform: `translateX(-${currentSlide * 100}%)` }"
        >
          <div
            v-for="(image, index) in images"
            :key="index"
            class="carousel-item"
            :class="{ active: index === currentSlide }"
          >
            <img
              :src="image"
              style="margin: auto; width: 200px"
              alt="Carousel Image"
            />
          </div>
        </div>
        <button class="carousel-btn prev-btn" @click="prevSlide">Prev</button>
        <button class="carousel-btn next-btn" @click="nextSlide">Next</button>
      </div>
      <div
        class="plus"
        style="font-size: 50px; font-weight: bold; color: #6b82bd"
      >
        +
      </div>
      <div class="card">
        <img
          style="margin-right: 10px; width: 200px"
          src="@/assets/postcard.jpg"
        />
      </div>
    </div>
  </div>
  <div style="margin-bottom: 20px">
    <a target="_blank" href="https://www.instagram.com/tofudesukedo/">
      <img
        style="margin-right: 10px; width: 50px"
        src="@/assets/instagram.jpeg"
      />
    </a>
    <a
      target="_blank"
      href="https://www.tiktok.com/@torubunol?is_from_webapp=1&sender_device=pc"
    >
      <img
        style="margin-bottom: 3px; margin-right: 15px; width: 50px"
        src="@/assets/tikto.png"
      />
    </a>
    <a target="_blank" href="https://www.facebook.com/tofudesukedo/">
      <img
        style="margin-right: 10px; width: 50px; margin-bottom: 1px"
        src="@/assets/facebook.jpeg"
      />
    </a>
  </div>
  <a href="http://tofudesukedo.github.io/dist"
    >特定商取引法に基づく表記用ページ</a
  >
</template>

<script>
export default {
  data() {
    return {
      currentSlide: 0,
      images: [
        require("@/assets/ero.jpg"),
        require("@/assets/emo.jpg"),
        require("@/assets/melon.jpg"),
        require("@/assets/sakura.jpg"),
      ],
    };
  },
  methods: {
    nextSlide() {
      this.currentSlide = (this.currentSlide + 1) % this.images.length;
    },
    prevSlide() {
      this.currentSlide =
        (this.currentSlide - 1 + this.images.length) % this.images.length;
    },
  },
};
</script>

<style>
.carousel {
  position: relative;
  overflow: hidden;
  width: 100%;
  max-width: 318px;
  margin: auto;
}

.carousel-inner {
  display: flex;
  transition: transform 0.5s ease;
}

.carousel-item {
  min-width: 100%;
  transition: opacity 0.5s ease;
}

.carousel-item img {
  width: 100%;
  display: block;
}

.carousel-btn {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  background-color: #6b82bd;
  color: white;
  border: none;
  border-radius: 50%;
  padding: 15px;
  cursor: pointer;
  transition: background-color 0.3s ease, transform 0.3s ease;
}

.carousel-btn:hover {
  background-color: #9fb0dd;
}

.carousel-btn:active {
}

.prev-btn {
  left: 10px;
}

.next-btn {
  right: 10px;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
h1 {
  margin-bottom: 0.2rem;
  border-bottom: 3px solid #b2d5de;
  font-weight: bold;
  font-size: 26px;
  width: fit-content;
  margin: 0 auto;
}

.flex-box {
  width: 100%;
  display: flex;
  text-align: center;
}

@media (max-width: 600px) {
  .flex-box {
    flex-direction: column;
  }
}

@media (min-width: 601px) {
  .flex-box {
    flex-direction: row;
    justify-content: space-around;
  }
  .carousel {
    width: 300px;
    margin: auto 0 auto auto;
  }
  .card {
    width: 150px;
    padding-right: 50px;
    margin: auto;
  }
  .plus {
    width: 50px;
    margin: auto;
  }
}
</style>
