<template>
  <v-app >
<v-main>
    <v-parallax class="mx-auto"
    height="750"
    style="background-color: #EF4040;"
    src = "@/assets/imagem2.jpeg"
  >
  <v-container style="font-family: system-ui; background-color: none; color: #fbdccc; font-size: 60px; opacity: 0.8;">
    Hi ! I'm Tyler Durden...</v-container>
  
</v-parallax>
  
  <v-container fluid style="background-color: #711DB0;">
    <hello-world/>
  </v-container>
</v-main> 
  </v-app>
</template>

<script>
import HelloWorld from '../components/CardsInfo.vue'

export default {
  name: 'HomeView',

  components:{HelloWorld}
  }

  

</script>
