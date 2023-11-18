<template>
  <header class="header py-3 px-5 d-flex bg-white">
    <img src="./assets/images/logo-main.svg" alt="">
    <ul class="menu-box ms-auto m-0 p-0">
      <li><a href="" class="d-block menu-option py-2">候選人主張</a></li>
      <li><a href="" class="d-block menu-option py-2">最新活動</a></li>
      <li><a href="" class="d-block menu-option py-2">政策議題</a></li>
      <li><a href="" class="d-block menu-option py-2">民眾服務信箱</a></li>
      <li><button class="btn btn-lg btn-primary rounded-pill fw-bold">我要捐款</button></li>
    </ul>
  </header>
</template>

<script>
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
  font-family: 'Noto Sans TC', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: var(--main-color);
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

</style>
