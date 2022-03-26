<template>
  <div class="jumbo jumbotron container-fluid">
    <img src="../assets/vue-jumbotron.jpg" />
    <h1>VUE Jumbotron!</h1>
  </div>
</template>

<script>
export default {
  name: "JumbotronVue",
};
</script>

<style scoped lang="scss">
img {
  width: 100%;
  height: auto;
}
h1 {
  position: absolute;
  color: white;
  font-size: 3rem;
  font-weight: bold;
  top: 70%;
  right: 70%;
}
</style>
