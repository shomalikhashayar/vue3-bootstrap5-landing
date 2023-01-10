<template>
  <div class="container my-5">
    <div class="row">
      <div class="col-md-7">
        <img src="https://picsum.photos/id/289/600/400" alt="khashayar" />
      </div>
      <div class="col-md-5 my-5">
        <h1 class="font-weight-light">Welcome...</h1>
        <p class="mt-4">
          My name is <mark> Khashayar Shomali</mark>, I'm Junior Frontend
          Developer and this is my first landing page I made by vue3 and
          bootstrap5.
        </p>
        <button
          type="button"
          class="btn btn-primary btn-lg"
          @click="
            openInNewTab('https://uixwithme.com/khashayar-shomali-portfolio/')
          "
        >
          Check my portfolio
        </button>
        <button
          type="button"
          class="btn btn-outline-primary btn-lg my-4"
          @click="openInNewTab('https://github.com/shomalikhashayar')"
        >
          Visit my GitHub
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Jumbotron",
  methods: {
    openInNewTab(url) {
      window.open(url, "_blank", "noreferrer");
    },
  },
};
</script>

<style scoped>
P {
  font-size: 22px;
}
button {
  margin: 5px;
}
</style>
