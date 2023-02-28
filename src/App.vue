<!-- IMPORTO IL COMPONENTE DELLA SUA SORGENTE -->
<script>
import Header from "./components/Header.vue";
import ContentGoes from "./components/ContentGoes.vue";
import BlueMenu from "./components/ShopAndSub.vue";
import UpperFooter from "./components/UpperFooter.vue";
import BottomFooter from "./components/BottomFooter.vue";

// STABILISCO CHE VADO A PRENDERE IL COMPONENTE CON NOME ....
export default {
  components: { Header, ContentGoes, BlueMenu, UpperFooter, BottomFooter },
};
</script>
<!-- NEL TEMPLATE INSERISCO IL NOME DEL MIO COMPONENTE FONDAMENTALMENTE IN UN SELF-CLOSING TAG -->
<template>
  <Header />
  <ContentGoes />
  <BlueMenu />
  <UpperFooter />
  <BottomFooter />
</template>
<!-- NELL'APP.VUE LO STYLE NON HA LO SCOPED -->
<style lang="scss"></style>
