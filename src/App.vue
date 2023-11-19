<template>
  <header class="header py-3 px-5 d-flex bg-white position-sticky top-0 z-3">
    <img src="./assets/images/logo-main.svg" alt="">
    <ul class="menu-box ms-auto m-0 p-0">
      <li><a href="" class="d-block menu-option py-2">候選人主張</a></li>
      <li><a href="" class="d-block menu-option py-2">最新活動</a></li>
      <li><a href="" class="d-block menu-option py-2">政策議題</a></li>
      <li><a href="" class="d-block menu-option py-2">民眾服務信箱</a></li>
      <li><button class="btn btn-lg btn-primary rounded-pill fw-bold">我要捐款</button></li>
    </ul>
  </header>
  <div class="main-box pt-4 px-8">
    <div class="position-relative">
      <div class="d-flex align-items-center">
        <div class="d-flex flex-column align-items-start me-auto">
          <h3 class="title title-md m-0">2023 THE F2E 立委競選</h3>
          <h2 class="title title-lg m-0 text-primary">從<span class="text-secondary">喵</span>的眼中</h2>
          <h2 class="title title-lg m-0 text-primary">看見台灣</h2>
        </div>
        <img src="./assets/images/miao-li-han_1x.png" alt="喵立翰照片" class="d-block z-1 me-7">
      </div>
      <img src="./assets/images/miao-li-han_text_1x.png" alt="喵立翰姓名" class="d-block position-absolute top-0 end-0">
      <img src="./assets/images/miao-li-han_text_en_1x.png" alt="喵立翰英文" class="d-block position-absolute bottom-0 start-0 ms-7 mb-4">
    </div>
    <div class="pb-6 position-relative">
      <div class="px-6 py-5 bg-white main-content">
        <h3 class="h1 fw-bold mb-5">護航台灣幸福經濟  從照顧每一隻貓咪開始</h3>
        <p class="h4 text-start mb-5 fw-bold">我堅信，藉由推動更完善的貓咪福利和相關政策，更是間接地投資於台灣的未來。畢竟，民眾的身心健康與工作熱情是推動經濟的核心動力。透過完善的貓咪福利政策，為台灣的 GDP 經濟帶來巨大效益。</p>
        <p class="h4 text-start m-0 fw-bold">因此，我期望能在立法院內推進這些政策，確保每一隻貓咪都能得到他們應有的照顧，同時也為台灣的經濟發展助一臂之力。</p>
      </div>
      <img src="./assets/images/arrow.png" alt="裝飾箭頭" class="d-block position-absolute bottom-0 start-0 mb-5">
    </div>
    <div class="pb-6">
      <h3 class="title title-normal mb-4">最新活動</h3>
      <div class="row">
        <div class="col-5">
          <div class="event-card-lg rounded-2 position-relative">
            <div class="card-tag-lg py-2 px-3 position-absolute top-0 end-0 bg-secondary rounded-top-2">
              <span class="d-block h2 text-white fw-bold">26</span>
              <span class="d-block h6 text-white fw-bold">DEC.</span>
            </div>
            <div class="event-card-img rounded-top-2"></div>
            <div class="p-3 bg-white rounded-bottom-2">
              <h4 class="h4 text-start fw-bold mb-2">參與台北寵物論壇 爭取貓咪友善環境</h4>
              <p class="text-start fw-medium m-0">炎炎夏日的周六，我走進了台北寵物論壇，帶著一副貓耳髮箍，決定要全力宣傳「貓咪至上」的理念！我相信，我們的都市中，每一隻貓咪都應該有自己的 VIP 休憩空間。</p>
            </div>
          </div>
        </div>
        <div class="col-7 d-flex flex-column">
          <div class="event-card rounded-2 d-flex mb-3 h-100">
            <div class="event-card-img-1 rounded-start-2"></div>
            <div class="p-3 bg-white rounded-end-2 d-flex flex-column align-items-start">
              <div class="card-tag">2023.12.20</div>
              <h4 class="h4 text-start fw-bold my-3" style="min-width: 375px;">帶著你的貓耳，來和我一起走！</h4>
              <p class="text-start fw-medium m-0">街上氣氛真的很棒，從小孩到大人，甚至有些狗狗朋友都帶著貓耳來找我握手，真的太可愛了！這次的活動不僅讓我看到大家的熱情，更加堅定了我推進「貓咪友善環境」政策的決心。</p>
            </div>
          </div>
          <div class="event-card rounded-2 d-flex h-100">
            <div class="event-card-img-2 rounded-start-2"></div>
            <div class="p-3 bg-white rounded-end-2 d-flex flex-column align-items-start">
              <div class="card-tag">2023.12.20</div>
              <h4 class="h4 text-start fw-bold my-3" style="min-width: 375px;">收容所模特兒大比拼！</h4>
              <p class="text-start fw-medium m-0">活動三消息內容：今天的收容所不再是一片寂靜。為了讓更多人認識到這裡的毛孩子，我們舉辦了一場前所未有的「模特兒走秀」！</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import './styles/global.scss'
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style lang="scss">
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}

body {
  margin: 0;
  background-color: var(--background-color);
}

.menu-box {
  display: flex;
  align-items: center;
  gap: 50px;
  list-style: none;
  position: relative;
  .menu-option {
    color: #000000;
    font-size: 1.25rem;
    font-weight: 700;
    text-decoration: none;
    position: relative;
    &::after {
      content: "";
      position: absolute;
      display: block;
      width: 0;
      height: 3px;
      background-color: var(--main-color);
      bottom: 1px;
      left: 1px;
      transition: .3s;
    }
    &:hover::after {
      content: "";
      position: absolute;
      display: block;
      width: 100%;
      height: 3px;
      bottom: 1px;
      right: 0;
      transition: .3s;
    }
  }
}

.main-content {
  margin-left: 10rem;
  border: 5px solid var(--main-color);
  border-radius: 80px 0px;
  box-shadow: -15px 20px 0px 0px #4527A0;
}

.event-card-lg {
  .event-card-img {
    background-image: url(./assets/images/event-reading.png);
    background-position: center;
    background-size: cover;
    width: 100%;
    height: 420px;
  }
}

.event-card {
  .event-card-img-1 {
    background-image: url(./assets/images/event-campaign.png);
    background-position: center;
    background-size: cover;
    width: 150%;
  }
  .event-card-img-2 {
    background-image: url(./assets/images/event-catwalk.png);
    background-position: center;
    background-size: cover;
    width: 150%;
  }
}

.card-tag {
  display: inline-flex;
  color: white;
  font-size: 1rem;
  font-weight: 500;
  padding: 0.25rem 1.25rem;
  border-radius: 8px 0px;
  background-color: var(--secondary-color);
}

</style>
