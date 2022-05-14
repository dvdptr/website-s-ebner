<template>
  <div class="font-medium">
    <Header />
    <Angebot />
    <Kontakt />
    <Footer />
  </div>
</template>

<script>
import Header from "~/components/Header.vue";
import Kontakt from "~/components/Kontakt.vue";
import Angebot from "~/components/Angebot.vue";
import Footer from "~/components/Footer.vue";

export default {
  components: {
    Header,
    Kontakt,
    Angebot,
    Footer
  },
  head() {
    return {
      title: "Simone Ebner Psychologische Praxis: Angebote"
    };
  }
};
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
  @apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
</style>
