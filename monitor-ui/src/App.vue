<template>
  <div id="app" class="c-dark">
    <router-view />
  </div>
</template>

<script>
export default {
  name: "app"
};
</script>

<style>
@import "./assets/css/global.css";
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  line-height: inherit;
  font-size: 12px;
}
</style>
