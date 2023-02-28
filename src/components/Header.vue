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
  <div class="container">
    <div><img src="../assets/img/dc-logo.png" alt="dc-logo" /></div>
    <ul>
      <li v-for="link in links" :key="text">
        <a href="#">{{ link.text }}</a>
      </li>
    </ul>
  </div>
</template>

<style lang="scss" scoped>
.container {
  margin: 0 auto;
  width: 1200px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  li {
    font-weight: 700;
  }
}
ul {
  width: 850px;
  list-style: none;
  display: flex;
  justify-content: space-between;
}
li {
  margin: 0 auto;
  a {
    text-decoration: none;
    color: inherit;
  }
}
</style>
