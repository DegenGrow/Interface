<template>
  <div class="container-fluid fixed-top mt-5">
    <div class="row">
      <div class="col d-flex justify-content-between">
        <img src="../assets/degenlogo.png" class="img-fluid mt-3" alt="" />

        <div>
          <ButtonComponent text="Buy $DegenGrow" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import ButtonComponent from "./Button.vue";
export default {
  name: "LogoHeader",

  components: {
    ButtonComponent,
  },
};
</script>
<style scoped>
img {
  height: 4rem;
  width: 4rem;
}
</style>
