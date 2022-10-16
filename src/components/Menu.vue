<!-- eslint-disable vue/multi-word-component-names -->
<template>
  <div class="container mt-3 mb-5">
    <div class="row">
      <div class="col-12 d-flex justify-content-between align-items-center">
        <div>
          <a href="#">
            <img
              class="img-fluid mt-4"
              style="width: 40px; height: 40px"
              src="../assets/degenlogo.png"
              alt=""
            />
          </a>

          <ButtonTransparent text="Vault" />
        </div>
        <div class="">
          <a href="#tokenomics" style="text-decoration: none">
            <p class="mt-2"></p>
          </a>
        </div>
      </div>
    </div>
  </div>
  <!-- <LogoBtn /> -->
</template>

<script>
import ButtonTransparent from "../components/ButtonTransparent.vue";
export default {
  name: "MenuBar",
  components: { ButtonTransparent },
};
</script>

<style scoped>
.bgdark {
  background-color: black;
}
p {
  color: antiquewhite;
  margin: 0;
  padding: 0;
}
.smaller {
  font-size: 0.6rem;
}
</style>
