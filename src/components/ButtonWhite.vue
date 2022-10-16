<template>
  <button class="btn px-3 mt-4">{{ text }}</button>
</template>

<script>
export default {
  name: "ButtonWhite",
  props: {
    text: String,
  },
};
</script>
<style scoped>
.btn {
  border: 1px solid white;
  border-radius: 0 !important;
  color: white;
}
.btn:hover {
  background-color: white;
  color: black;
}
</style>
