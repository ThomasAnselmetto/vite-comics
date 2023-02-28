<script>
export default {
  data() {
    return {
      putTheContent: {
        type: "content",
        text: "-->Content goes here-->",
      },
    };
  },
};
</script>

<template>
  <section class="content-here">
    <div class="container">
      <h2>{{ putTheContent.text }}</h2>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.container {
  width: 1200px;
  margin: 0 auto;
  display: flex;
}
.content-here {
  height: 10rem;
  display: flex;
  align-items: center;
  background-color: black;
  color: white;
}
</style>
