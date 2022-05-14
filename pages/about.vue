<template>
  <div class="font-medium">
    <Header />
    <Person />
    <Praxis />
    <Kontakt />
    <Footer />
  </div>
</template>

<script>
import Header from "~/components/Header.vue";
import Kontakt from "~/components/Kontakt.vue";
import Person from "~/components/Person.vue";
import Praxis from "~/components/Praxis.vue";
import Footer from "~/components/Footer.vue";

export default {
  components: {
    Header,
    Kontakt,
    Person,
    Praxis,
    Footer
  },
  head() {
    return {
      title: "Simone Ebner Psychologische Praxis: Person & Praxis"
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
