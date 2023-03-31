<template>
  <VApp style="font-family: system-ui; font-weight: 300;">
  <v-app-bar elevation="4" color="#f32939" height="65" absolute>
      
      <v-btn style="font-size: 14px;"  variant="plain" color="#fbdccc" to="/">Home</v-btn>
      
      <v-btn  style="font-size: 14px;" variant="plain" color="#fbdccc" to="/about">Projects</v-btn>
      
      <v-btn style="font-size: 14px;" variant="plain" color="#fbdccc">Contact</v-btn>

      <v-btn style="font-size: 14px;" variant="plain" color="#fbdccc">Info</v-btn>
     
      <VSpacer></VSpacer>
      <VIcon size="large" color="#fbdccc" style="margin-right: 30px;">mdi-vuetify</VIcon>
     </v-app-bar>

     <VMain scrollable><RouterView/></VMain>
     
    </VApp>
  
</template>

<script>


export default {
    data() {
        return {
            drawer: false,
        };
    },
    
};
</script>
