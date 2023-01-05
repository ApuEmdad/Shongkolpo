<template>
  <div class="BodyContainer">
    <div class="BodyContainerTop">
      <BodyMain />
      <BodySideNav />
    </div>

    <BodyFooter />
  </div>
</template>
<script>
import BodyMain from "./BodyMain/BodyMain.vue";
import BodySideNav from "./BodySideNav/BodySideNav.vue";
import BodyFooter from "./BodyFooter/BodyFooter.vue";

export default {
  components: {
    BodyMain,
    BodySideNav,
    BodyFooter,
  },
};
</script>
<style>
@import "../CSS/Body.css";
</style>
