<script></script>

<template>
  <section class="bottom-footer">
    <div class="container">
      <div class="bottone">
        <button type="button">SIGN-IN NOW!</button>
      </div>
      <div class="socials">
        <H4>FOLLOW US</H4>
        <i class="fa-brands fa-facebook"></i>
        <i class="fa-brands fa-twitter"></i>
        <i class="fa-brands fa-youtube"></i>
        <i class="fa-brands fa-pinterest"></i>
        <i class="fa-solid fa-location-dot"></i>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.bottom-footer {
  height: 7rem;
  background-color: #303030;
}
.container {
  margin: 0 auto;
  width: 1200px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.bottone {
  padding: 2rem 0;
  button {
    border: 2px solid #0282f9;
    padding: 8px;
    background-color: transparent;
    color: white;
  }
}
.socials {
  width: 20rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 2rem 0;

  i {
    font-size: 25px;
    color: grey;
  }
  h4 {
    color: #0282f9;
  }
}
</style>
