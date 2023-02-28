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
          text: "Characters",
          active: "false",
        },
        {
          link: "#",
          text: "Comics",
          active: "false",
        },
        {
          link: "#",
          text: "Movies",
          active: "false",
        },
        {
          link: "#",
          text: "Tv",
          active: "false",
        },
        {
          link: "#",
          text: "Games",
          active: "false",
        },
        {
          link: "#",
          text: "Collectibles",
          active: "false",
        },
        {
          link: "#",
          text: "Videos",
          active: "false",
        },
        {
          link: "#",
          text: "Fans",
          active: "false",
        },
        {
          link: "#",
          text: "News",
          active: "false",
        },
        {
          link: "#",
          text: "Shop",
          active: "false",
        },
      ],
    };
  },
};
</script>

<template>
  <section>
    <div class="container">
      <div class="texts">
        <div class="col-1">
          <h3>DC COMICS</h3>
          <ul>
            <li v-for="link in links" :key="text">{{ link.text }}</li>
          </ul>
          <h3>SHOP</h3>
          <ul>
            <li>Shop DC</li>
            <li>Shop DC Collections</li>
          </ul>
        </div>
        <div class="col-2">
          <h3>DC</h3>
          <ul>
            <li>Terms Of Use</li>
            <li>Privacy policy (New)</li>
            <li>Ad Choices</li>
            <li>Advertising</li>
            <li>Jobs</li>
            <li>Subscriptions</li>
            <li>Talent Workshops</li>
            <li>CPSC Certificates</li>
            <li>Ratings</li>
            <li>Shop Help</li>
            <li>Contact Us</li>
          </ul>
        </div>
        <div class="col-3">
          <h3>SITES</h3>
          <ul>
            <li>DC</li>
            <li>MAD Magazine</li>
            <li>DC Kids</li>
            <li>DC Universe</li>
            <li>DC Power Visa</li>
          </ul>
        </div>
      </div>
      <div class="jumbo-logo"></div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
section {
  height: 25rem;
  background-image: url(../assets/img/footer-bg.jpg);
  background-position: center;
  background-size: cover;
}
.container {
  margin: 0 auto;
  width: 1200px;
  display: flex;
  justify-content: space-between;
}
.texts {
  display: flex;
}
.jumbo-logo {
  height: 25rem;
  width: 35rem;
  background-image: url(../assets/img/dc-logo-bg.png);
  background-position: center;
}
h3 {
  color: white;
}
ul {
  list-style: none;
  color: gray;
}
</style>
