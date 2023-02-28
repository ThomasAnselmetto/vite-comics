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

<style scoped>
.content-here {
  height: 10rem;
  display: flex;
  align-items: center;
  background-color: black;
  color: white;
}
</style>
