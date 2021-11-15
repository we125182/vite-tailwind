<template>
  <div class="flex">
    <img class="shadow-xl mr-8 rounded-full" alt="Vue logo" src="./assets/logo.png" />
    <div class="text-left flex flex-col justify-center items-start">
      <HelloWorld msg="Hello Vue 3 + Vite" />
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import HelloWorld from "./components/HelloWorld.vue";

export default defineComponent({
  name: "App",
  components: {
    HelloWorld,
  },
});
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  padding: 32px;
  height: 100%;
  box-sizing: border-box;
  background-color: lightgoldenrodyellow;
}
</style>