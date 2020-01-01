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
      text: "我是好人"
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
