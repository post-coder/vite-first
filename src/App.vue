<script>
// il codice della logica della nostra app
import Title from "./components/Title.vue";
import Footer from "./components/Footer.vue";

export default {
  components: {
    Title,
    Footer
  }
}
</script>

<template>
  <!-- il layout della nostra app -->
  
  <Title></Title>

  Contenuto della mia pagina

  <Footer></Footer>
</template>

<style>
/* lo stile della nostra app */

</style>