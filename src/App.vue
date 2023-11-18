<template>
  <header class="header py-1 px-5">
    <img src="./assets/images/logo-main.svg" alt="">
  </header>
  <p>111</p>
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
  font-family: 'Mantou Sans', Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: var(--main-color);
}

body {
  margin: 0;
}

</style>
