<template>
  <div class="Title">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: "TitleText",
  props: {
    msg: String,
  },
};
</script>

<style scoped lang="scss"></style>
