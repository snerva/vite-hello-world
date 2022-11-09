<script>
import AppTitle from "./components/AppTitle.vue";
import AppHero from "./components/AppHero.vue";
export default {
  components: {
    AppTitle,
    AppHero
  }
}
</script>

<template>
  <AppHero></AppHero>
  <AppTitle></AppTitle>
</template>

<style>
.jumbotron {
  max-width: 100%;
  height: 320px;
  background-color: cadetblue;
  color: white;
  padding: 2rem;
}

h1 {
  font-size: 3.2rem;
}

p {
  margin: 2rem 0;
}

a {
  text-decoration: none;
  background-color: dodgerblue;
  color: white;
  border-radius: 10px;
  padding: 0.75rem;
}

h2 {
  text-align: center;
  font-size: 2.5rem;
  margin: 2rem;
}
</style>
