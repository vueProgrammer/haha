<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <div class="bottom">
      <p>备案号: <a href="https://beian.miit.gov.cn/">京ICP备2022018021号-1</a> </p>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>

<style>
.bottom {
  position: fixed;
  width: 100%;
  bottom: 0;
  left: 0;
  right: 0;
  background-color: #000;
  padding: 30px 0;
  font-size: 24px;
  color: #fff;
  text-align: center;
}
</style>
