<template>
  <v-app >
<v-main>
    <v-parallax
    height="750"
    src="https://miro.medium.com/max/1400/1*RoXcbaF9lIqwpMjiXg54Vw.png"
  >
  <v-container style="font-family: system-ui; background-color: none; color: #ff5c1b; font-size: 60px; opacity: 0.8;">
    Hi ! I'm Ivan...</v-container>
  <v-container style="font-family: system-ui; background-color: none; color: #ff5c1b; font-size: 60px; margin-left: 500px; opacity: 0.8; margin-top: 100px;">
    This is my portfolio page</v-container>
</v-parallax>
  
  <v-container fluid style="background-color: #fbdccc;">
    <div style="font-size: 24px;">Available products</div>
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
