<template>
<v-app>
    <v-main class="bg-secondary" color="">
      <Header/>
      <Hero />
      <Bio/>
      <Beneficios/>
      <Social/>
      <Footer/>
    </v-main>
  </v-app>
  
</template>

<script setup>
  import Header from '@/components/HeaderPage.vue'
  import Hero from '@/components/HeroPage.vue'
  import Bio from '@/components/BioPage.vue'
  import Beneficios from '@/components/BeneficioPage.vue'
  import Social from '@/components/SocialPage.vue';
  import Footer from '@/components/FooterPage.vue';
</script>
