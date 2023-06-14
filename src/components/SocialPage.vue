<template>
<v-container
fluid
  class=""
>
 <v-row dense class="align-center justify-center"
 v-for= "(imagen, index) in imagenes"
  :key="index" 
 >
   <v-col cols="sx-6 sm-auto" class="">
    <v-img
               v-if="(index) % 2 == 0"
                cover
                class="elevation-2"
                :src="getImageUrl(imagenes[index])"
    >
  </v-img>
   </v-col>
   <v-col cols="sx-6 sm-auto" class="">
    <v-img
                v-if="(index) % 2 !== 0"           
                cover
                class="elevation-2"
                :src="getImageUrl(imagenes[index])"
    >
  </v-img>
   </v-col>
 </v-row>
</v-container>
</template>
<script>export default {
  computed: {
    //
  },
  methods: {
    getImageUrl(imagen) {
        
      return `/src/assets/${imagen}`
    },
  },
  data: () => ({
    imagenes: [
      'm1.jpg',
      'm2.jpg',
      'm3.jpg',
      'm4.jpg'
    ]
  })
};
</script>