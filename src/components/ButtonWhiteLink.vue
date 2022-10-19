<template>
  <a href="https://app.uniswap.org/#/swap?outputCurrency=0x46ce776bca835d4f704072c28ab1d9a54f4b7b46" target="_blank">
    <button class="btn px-3 mt-4">{{ text }}</button></a
  >
</template>

<script>
export default {
  name: "ButtonWhiteLnk",
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
