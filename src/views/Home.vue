<template>
  <div class="home">
    <img class="logo" alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App" />
    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App" />
    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App" />
    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App" />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src

@Component({
  components: {
    HelloWorld
  }
})
export default class Home extends Vue {}
</script>

<style lang="less">
.home {
  padding: 36px;
  .logo {
    width: 200px;
    height: 200px;
  }
}
</style>
