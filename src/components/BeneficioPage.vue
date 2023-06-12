<template>
  <v-container
      class=""
    >
    <v-row class="align-center justify-center">
        <v-col cols="sx-2 sm-4" class="mr-2 pa-0 text-center">
            <div class="mb-4 " style="font-size: 14px;font-weight: 500;line-height: 14px;">
                Para mis lindas clientes les tengo este obsequio en su primera cita.
            </div>
            <div class="text-h5 mb-4" style="font-size: 16px;font-weight: 500;line-height: 18px;">
              20% decuento.
            </div>
            <v-btn elevation="8" color="primary" size="small" @click="whatsapp">Contáctenos</v-btn>
        </v-col>
        <v-col cols="sx-2 sm-4" class="ml-2 pa-0">
            <v-img

                cover
                class="elevation-8"
                src= "/src/assets/tratamiento.webp"
              >
            </v-img> 
        </v-col>
      </v-row>
      <v-row class="justify-center">
      <v-col cols="auto" class="">
          <v-img
             Height= "26"
             width="320"
             src= "/src/assets/SeperadorDown.png"
          >
          </v-img>
      </v-col>
    </v-row>
   </v-container>
</template>
<script setup>
  //
     function whatsapp() {
      window.location.href = 'https://wa.me/50767883873/?text=Hola%20deseo%20agendar%20una%20cita%20desde%20tu%20web...'
       //acciones a realizar
     }
</script>
<style>

</style>