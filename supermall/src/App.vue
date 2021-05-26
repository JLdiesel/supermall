<template>
  <div id="nav"></div>
  <main-tab-bar id="mainTabBar" />
  <router-view />
</template>
<script>
import MainTabBar from "components/content/mainTabbar/MainTabBar";
export default {
  name: "App",
  components: {
    MainTabBar,
  },
};
</script>
<style>
@import url("assets/css/base.css");
#mainTabBar {
  position: fixed;
  bottom: 0;
  left: 0;
  right: 0;
}
</style>
