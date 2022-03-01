<template>
  <the-nav></the-nav>
  <the-home></the-home>
  <the-products></the-products>
</template>
<script>
import TheNav from "./components/TheNav.vue";
import TheHome from "./views/Home.vue";
import TheProducts from "./views/TheProducts.vue";
import "./css/app.css";
export default {
  components: {
    TheNav,
    TheHome,
    TheProducts
  },
};
</script>
