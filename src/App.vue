<script>//setup
import titolo from "./components/AppTitle.vue";
import jumbo from "./components/Jumbotron.vue";

export default {
  //chiamata componets
  components: {
    titolo,
    jumbo,
  }
}

</script>

<template>
  <jumbo/>
  <h1>ciao</h1>
  
  <titolo/>
</template>

<style scoped>

</style>
