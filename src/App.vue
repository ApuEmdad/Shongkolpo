<template>
  <header class="container">
    <NogorJibon />
  </header>
</template>

<script>
import NogorJibon from "./Pages/NogorJibon/NogorJibon.vue";
import Body from "./components/Body/Body.vue";
export default {
  name: "App",
  components: {
    NogorJibon,
    Body,
  },
};
</script>

<style>
@import url("https://fonts.cdnfonts.com/css/segoe-ui-4");

* {
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.container {
}
</style>
