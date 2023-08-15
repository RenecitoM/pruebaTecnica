<template>
  <div id="app">
    <Header class="header"></Header>
    <BodyCommuny class="body"></BodyCommuny>
    <cards></cards>
    <Leading></Leading>
    <CommuniTraders></CommuniTraders>
  </div>
</template>

<style scoped>
.header {
  position: relative; 
  z-index: 2; 
}

.body {
  position: relative;
  z-index: 4; 
}
</style>

<script>
import Header from "./components/Header.vue";
import BodyCommuny from "./components/BodyCommuny.vue";
import cards from "./components/Cards.vue";
import Leading from "./components/Leading.vue";
import CommuniTraders from "./components/CommuniTraders.vue";

export default {
  components: {
    Header,
    BodyCommuny,
    cards,
    Leading,
    CommuniTraders,
  },
};
</script>