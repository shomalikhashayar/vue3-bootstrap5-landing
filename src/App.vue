<template>
  <Navbar />
  <Jumbotron />
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Jumbotron from "./components/Jumbotron.vue";

export default {
  name: "App",
  components: {
    Navbar,
    Jumbotron,
  },
};
</script>

<style></style>
