<template>
  <v-container fluid class="">
    <v-row dense class="align-center">
      <v-col cols="6" class="" v-for="imagen in imagenes">
        <v-img cover class="elevation-2" :src="getImageUrl(imagen)">
        </v-img>
      </v-col>
    </v-row>
  </v-container>
</template>
<script>
export default {
  computed: {
    //
  },
  methods: {
    getImageUrl(imagen) {
      return `/src/assets/${imagen}`;
    },
  },
  data: () => ({
    imagenes: ["m1.jpg", "m3.jpg", "m2.jpg", "m4.jpg"],
  }),
};
</script>
