<template>
<div>
  <Header />
  <Hero />
  <About />
  <Kontakt />
  <Footer />
  
  </div>
  
</template>

<script>

import Header from "~/components/Header.vue";
import Hero from "~/components/Hero.vue";
import About from "~/components/About.vue";
import Kontakt from "~/components/Kontakt.vue";
import Footer from "~/components/Footer.vue";

export default {
  components: {
    Header,
    Hero,
    About,
    Kontakt,
    
    Footer
  },
  head() {
    return {
      title: "Simone Ebner Psychologische Praxis",
      meta: [
        { charset: "utf-8" },
        { name: "viewport", content: "width=device-width, initial-scale=1" },
        {
          hid: "description",
          name: "description",
          content:
            "Simone Ebner Psychologische Praxis"
        }
      ]
    };
  }
};
</script>

<style>
html {
  font-family: "Inter", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
    "Helvetica Neue", Arial, sans-serif;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

.pylg {
  @apply py-16;
}
</style>
