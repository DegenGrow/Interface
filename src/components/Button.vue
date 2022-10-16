<template>
  <button class="btn px-3 mt-4">{{ text }}</button>
</template>

<script>
export default {
  name: "ButtonComponent",
  props: {
    text: String,
  },
};
</script>
<style scoped>
.btn {
  border: 1px solid black;
  border-radius: 0 !important;
}
.btn:hover {
  background-color: black;
  color: antiquewhite;
}
</style>
