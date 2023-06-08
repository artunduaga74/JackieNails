<template>
  <v-footer class="elevation-8 d-flex flex-column bg-secondary">
    <div class="align-center px-4 text-center" style="font-size: 12px;font-weight: 400;">
      Visitanos en nuestras redes sociales.
    </div>
    <div class="text-center">
      <v-btn elevation="8" v-for="icon in icons" 
        :href="dirs"
        :key="icon" class="mx-4" 
        :icon="icon" variant="plain" 
        size="">
      </v-btn>
    </div>
    <div class="px-4 py-2 text-center text-caption text-bold">
      Orion Web Desing 2023
    </div>
  </v-footer>
</template>

<script>
export default {
  data: () => ({
    icons: [
    'mdi-facebook',
    'mdi-instagram',
    ],
    dirs:
    [
      'https://www.instagram.com/nailsby_jackeline/',
      'https://www.instagram.com/nailsby_jackeline/',
    ]
  }),
}
</script>
