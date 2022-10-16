<template>
  <button class="btn px-3 mt-4 ms-3">{{ text }}</button>
</template>

<script>
export default {
  name: "ButtonTransparent",
  props: {
    text: String,
  },
};
</script>
<style scoped>
.btn {
  color: white;
}
.btn:hover {
  /* background-color: white; */
  /* color: black; */

  border: 1px solid white;
  /* border-radius: 0 !important; */
}
</style>
