<template>
  <Navbar />
  <Jumbotron />
  <CTA />
  <Cards />
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Jumbotron from "./components/Jumbotron.vue";
import CTA from "./components/CTA.vue";
import Cards from "./components/Cards.vue";

export default {
  name: "App",
  components: {
    Navbar,
    Jumbotron,
    CTA,
    Cards,
  },
};
</script>

<style>
body {
  background-color: aliceblue;
}
</style>
