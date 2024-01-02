<template>
  <VApp style="font-family: system-ui; font-weight: 300;">
  <v-app-bar elevation="8" color="#711DB0" height="60" >
      
      <v-btn style="font-size: 14px;"  variant="tonal" color="#fbdccc" to="/">Home</v-btn>
      
      <v-btn  style="font-size: 14px;" variant="tonal" color="#fbdccc" to="/about">About me</v-btn>

      <v-btn style="font-size: 14px;" variant="tonal" color="#fbdccc">My arts</v-btn>
      
      <VSpacer></VSpacer>
      <VIcon size="large" color="#C21292" style="margin-right: 30px;">mdi-vuetify</VIcon>
     </v-app-bar>

     <VMain scrollable><RouterView/></VMain>
     
    </VApp>
  
</template>

<script>


export default {
    data() {
        return {
           
        };
    },
    
};
</script>
