<template>
  <div id="app">
    <MainTabbar />
    <router-view />
  </div>
</template>

<script>
import MainTabbar from "./components/tabbar/MainTabbar";

export default {
  name: "App",
  components: {
    MainTabbar
  }
};
</script>
<style>
</style>
