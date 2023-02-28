<script>
export default {
  data() {
    return {};
  },
};
</script>

<template>
  <section>
    <div class="container">
      <div class="shop-card">
        <img
          src="../assets/img/buy-comics-digital-comics.png"
          alt="buy-comics"
        />
        <h5>DIGITAL COMICS</h5>
      </div>
      <div class="shop-card">
        <img src="../assets/img/buy-comics-merchandise.png" alt="merchandise" />
        <h5>DC MERCHANDISE</h5>
      </div>
      <div class="shop-card">
        <img
          src="../assets/img/buy-comics-shop-locator.png"
          alt="shop-locator"
        />
        <h5>SUBSCRIPTION</h5>
      </div>
      <div class="shop-card">
        <img
          src="../assets/img/buy-comics-subscriptions.png"
          alt="subscription"
        />
        <h5>COMIC SHOP LOCATOR</h5>
      </div>
      <div class="shop-card">
        <img src="../assets/img/buy-dc-power-visa.svg" alt="power-visa" />
        <h5>DC POWER VISA</h5>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
section {
  padding: 2rem 0;
  background-color: #0282f9;
  img {
    max-height: 4rem;
  }
}
.container {
  margin: 0 auto;
  width: 1200px;
  display: flex;
  justify-content: space-evenly;
}

.shop-card {
  display: flex;
}
.shop-card h5 {
  align-self: flex-end;
  color: white;
}
</style>
