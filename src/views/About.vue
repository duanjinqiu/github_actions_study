<template>
  <div class="about">
    <h1>This is an about page</h1>
    <p class="red">{{ text }}</p>
  </div>
</template>

<script>
export default {
  name: "About",
  data() {
    return {
      text: ""
    };
  },
  created() {}
};
</script>

<style lang="scss" scoped>
    .red {
        color: red;
    }
</style>
