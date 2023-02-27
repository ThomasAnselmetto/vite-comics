<script>
export default {
  data() {
    return {
      logo: {
        src: "",
        title: "dc-logo",
      },
      links: [
        {
          link: "#",
          text: "CHARACTERS",
          active: "false",
        },
        {
          link: "#",
          text: "COMICS",
          active: "false",
        },
        {
          link: "#",
          text: "MOVIES",
          active: "false",
        },
        {
          link: "#",
          text: "TV",
          active: "false",
        },
        {
          link: "#",
          text: "GAMES",
          active: "false",
        },
        {
          link: "#",
          text: "COLLECTIBLES",
          active: "false",
        },
        {
          link: "#",
          text: "VIDEOS",
          active: "false",
        },
        {
          link: "#",
          text: "FANS",
          active: "false",
        },
        {
          link: "#",
          text: "NEWS",
          active: "false",
        },
        {
          link: "#",
          text: "SHOP",
          active: "false",
        },
      ],
    };
  },
};
</script>

<template>
  <ul>
    <li><img src="../assets/img/dc-logo.png" alt="dc-logo" /></li>
    <li v-for="link in links" :key="text">{{ link.text }}</li>
  </ul>
</template>

<style scoped>
ul {
  list-style: none;
  display: flex;
}
li {
  margin: 0 auto;
}
</style>
