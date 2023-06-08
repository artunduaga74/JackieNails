<template>

  <v-container
          fluid
          class="pa-4"
          width="322px"
        >
         <v-row class="">
           <v-col  class="mr-2 text-center" >
            <div class="text-h6 mb-4" style="line-height: 18px">
              Expresa Tu Estilo con Manos Impresionantes
            </div>
            <div class="mb-4" style="font-size: 12px;font-weight: 500;line-height: 14px;">
              Vamos consiente tus uñas en un espacio exclusivo, creado para ti.
            </div>
            <v-btn color="primary" size="small">Contáctenos</v-btn>
           </v-col>
           <v-col class="ml-2 pa-0 aling-center" cols="auto">
            <v-img
              cover
              height="150"
              width="183"
                class=""
                src= "src/assets/hero.png"
              >
            </v-img> 
           </v-col>
           
       </v-row>
</v-container>
</template>

<script setup>
  //
</script>
<style>
.row{
  border-radius: 2px;
  border-color: red;
}
</style>
