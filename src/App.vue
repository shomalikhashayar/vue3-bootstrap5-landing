<template>
  <Navbar />
  <Jumbotron />
  <CTA />
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Jumbotron from "./components/Jumbotron.vue";
import CTA from "./components/CTA.vue";

export default {
  name: "App",
  components: {
    Navbar,
    Jumbotron,
    CTA
  },
};
</script>

<style>
body {
  background-color: aliceblue;
}
</style>
