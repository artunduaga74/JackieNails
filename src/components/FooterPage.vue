<template>
  <v-footer class="d-flex flex-column bg-secondary">
    <div class="align-center px-4 text-center">
      <strong>Visitanos en nuestras redes sociales.</strong>
    </div>
    <div class="text-center w-100">

      <v-btn v-for="icon in icons" :key="icon" class="mx-4" :icon="icon" variant="plain" size="small"></v-btn>
    </div>
 
    <div class="px-4 py-2 text-center w-100">
      <strong>Orion Web Desing 2023</strong>
     

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
  }),
}
</script>
