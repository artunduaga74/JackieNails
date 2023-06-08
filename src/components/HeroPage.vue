<template>
  <v-container
          fluid
          class="pa-4"
          width="322px"
        >
      <v-row  no-gutter class="align-center justify-center">
      <v-col cols="auto">
          <v-img
          cover
             Height= "26"
             width="320"
             src= "/src/assets/SeparadorUp.png"
          >
          </v-img>
      </v-col>
    </v-row>
         <v-row class="justify-center align-center">
           <v-col cols="xs-2 sm-auto" class="mr-2 text-center" >
            <div class="mb-4" style="font-size: 18px;font-weight: 500; line-height: 18px">
              Expresa Tu Estilo con Manos Impresionantes
            </div>
            <div class="mb-4" style="font-size: 15px;font-weight: 400;line-height: 14px;">
              Vamos consiente tus uñas en un espacio exclusivo, creado para ti.
            </div>
            <v-btn elevation="8" color="primary" size="small" @click="whatsapp">Contáctenos</v-btn>
           </v-col>
           <v-col class="ml-2 pa-0" cols="xs-4 sm-auto">
            <sheet class="" >
              <v-img
                cover
                height="100%"
                class="elevation-4"
                src= "/src/assets/hero.png"
              >
            </v-img>
            </sheet>
 
           </v-col>
           
       </v-row>
</v-container>
</template>

<script>
  //
  export default {
    methods: {
     whatsapp: function(){
      window.location.href = 'https://wa.me/50762254433/?text=Hola%20deseo%20agendar%20una%20cita%20desde%20tu%20web...'
       //acciones a realizar
     },
    }
  }
</script>
<style>

</style>
