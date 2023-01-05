<template>
  <div class="main-cards-container">
    <Card />
    <Card />
    <Card />
    <Card />
    <Card />
    <Card />
  </div>
</template>
<script>
import Card from "./Card.vue";
export default {
  components: {
    Card,
  },
  data() {
    cards: [1, 2, 3, 4, 5, 6];
  },
};
</script>
<style>
@import "../../../CSS/MainCards.css";
</style>
