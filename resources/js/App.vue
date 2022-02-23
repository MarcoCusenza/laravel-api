<template>
  <div class="page-container">
    <Header />
    <Main />
    <Footer />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Main,
    Footer,
  },
};
</script>

<style>
body {
  background-color: rgb(76, 84, 84);
  /* font-weight: bold; */
}

.button-link {
  color: rgb(0, 0, 0);
  background-color: #1ea896;
  padding: 8px;
  border-radius: 5px;
  margin-left: 3px;
  transition: 0.6s ease-in-out;
}

.button-link:hover {
  text-decoration: none;
  background-color: #000000;
  color: whitesmoke;
  transition: 1.2s ease-in-out;
}
</style>