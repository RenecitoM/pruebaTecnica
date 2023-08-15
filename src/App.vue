<template>
  <div id="app">
    <Header class="header"></Header>
    <BodyCommuny class="body"></BodyCommuny>
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

export default {
  components: {
    Header,
    BodyCommuny,
  },
};
</script>