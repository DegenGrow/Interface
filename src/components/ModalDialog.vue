<template>
  <!-- Button trigger modal -->
  <!-- <button
    type="button"
    class="btn"
    data-bs-toggle="modal"
    data-bs-target="#exampleModal"
  >
    Launch demo modal
  </button> -->

  <ButtonWhite text="Get $DGROW" />

  <ButtonWhiteLink text="Spend" />

  <!-- Modal -->
  <div
    class="modal fade"
    id="exampleModal"
    tabindex="-1"
    aria-labelledby="exampleModalLabel"
    aria-hidden="true"
  >
    <div class="modal-dialog modal-dialog-centered text-white">
      <div class="modal-content bg-dark">
        <div class="modal-header">
          <h1 class="modal-title fs-5" id="exampleModalLabel">
            Search, observation, analysis.
          </h1>
          <button
            type="button"
            class="btn-close"
            data-bs-dismiss="modal"
            aria-label="Close"
          ></button>
        </div>
        <div class="modal-body">
          <p>
            It seems you are a lost traveler, but you have a compass, it will
            show the way. Even among the many monophonic threads that enveloped
            the view, having considered among them only one with slight
            differences, will lead you to where the sunset is coming.
          </p>
        </div>
        <div class="p-3">
          <form>
            <div class="form-floating">
              <input
                type="text"
                class="form-control border-start-0 border-end-0 border-top-0 shadow-none rounded-0 bg-transparent text-white"
                id="floatingInput"
                placeholder="name@example.com"
              />
              <label for="floatingInput"> Enter secret key</label>
            </div>
            <ButtonWhite text="Submit Secret Key" />
          </form>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// import ButtonComponent from "../components/Button.vue";
import ButtonWhite from "../components/ButtonWhite.vue";
import ButtonWhiteLink from "./ButtonWhiteLink.vue";
export default {
  name: "ModalDialog",
  components: {
    // ButtonComponent,
    ButtonWhite,
    ButtonWhiteLink,
  },
};
</script>

<style scoped>
.btnm {
  border: 1px solid white;
  border-radius: 0 !important;
  color: white;
}
.btnm:hover {
  background-color: white;
  color: black;
}
</style>
