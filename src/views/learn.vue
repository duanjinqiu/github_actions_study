<template>
  <div>
    教程地址
    <p>
      <a :href="url" v-text="url" title="点击访问教程页面"></a>
    </p>
  </div>
</template>

<script>

export default {
  data() {
    return {
      url:
        "http://www.ruanyifeng.com/blog/2019/09/getting-started-with-github-actions.html"
    };
  }
};
</script>

<style scoped>
a {
    color: rgb(16, 181, 223);
    font-size: 20px;
}
</style>