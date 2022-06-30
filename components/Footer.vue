<template>
  <div
    class="w-full  border-b border-gray-400 px-4 md:px-0 py-8 mx-auto md:flex justify-center text-white leading-tight text-sm bg-gray-700"
  >
    <div class="">
      <section class="py-4 mr-12">
        <LogoWhite class="h-10 fill-current text-white" />
      </section>
    </div>
    <div class="md:flex">
      <section class="py-4 mr-12">
        <p class="font-bold pb-1">M. Sc. Psych. Simone Ebner</p>
        Paulinstr. 75 <br />54292 Trier
        <br />
      </section>
      <section class="py-4 mr-12">
        <p class="font-bold pb-1">Kontakt</p>
        Mobil: 01573 18 94 114<br />e-Mail: <a href="mailto:simoneebner@posteo.de" target="_blank"
              >simoneebner@posteo.de</a>
      </section>
    </div>
    <section class="py-4 mr-12">
      <p class="font-bold pb-1">Links</p>
      <nuxt-link to="/impressum">Impressum</nuxt-link>
      <br />
      <nuxt-link to="/datenschutz">Datenschutz</nuxt-link>
    </section>
    
  </div>
</template>

<script>
// import LogoWhite from "@/components/LogoWhite.vue";
// export default {
//   components: {
//     LogoWhite
//   }
// };
</script>

<style></style>
