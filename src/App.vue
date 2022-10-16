<template>
  <section class="">
    <BodyHolder />
    <MenuBar />
    <BodyText />
  </section>
</template>

<script>
import MenuBar from "./components/Menu.vue";
import BodyText from "./components/BodyText.vue";
import BodyHolder from "./components/BodyHolder.vue";

export default {
  name: "App",
  components: {
    MenuBar,
    BodyText,
    BodyHolder,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: #fff;
  margin: 0;
  padding: 0;
}
</style>
