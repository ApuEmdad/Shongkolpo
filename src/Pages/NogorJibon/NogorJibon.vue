<template>
  <header>
    <Header />
  </header>
  <body class="body">
    <Body />
  </body>
</template>
<script>
import Header from "@/components/Header/Header.vue";
import Body from "@/components/Body/Body.vue";
export default {
  components: {
    Header,
    Body,
  },
};
</script>
<style></style>
