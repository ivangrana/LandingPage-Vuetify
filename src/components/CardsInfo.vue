
<template>
  <v-container fluid>
    <v-row>
    <VCol :cols="20">
    <v-card
    class="mx-auto"
    max-width="344"
  >
    <v-img
      src="@/assets/imagem1.jpeg"
      height="200px"
      cover
    ></v-img>

    <v-card-title>
      art #2
    </v-card-title>

    <v-card-subtitle>
      1,000 miles of wonder
    </v-card-subtitle>

    <v-card-actions>
      <v-btn
        color="#711DB0"
        variant="text"
      >
        Explore
      </v-btn>

      <v-spacer></v-spacer>

      <v-btn
        :icon="show ? 'mdi-chevron-up' : 'mdi-chevron-down'"
        @click="show = !show"
      ></v-btn>
    </v-card-actions>

    <v-expand-transition>
      <div v-show="show">
        <v-divider></v-divider>

        <v-card-text>
          I'm a thing. But, like most politicians, he promised more than he could deliver. You won't have time for sleeping, soldier, not with all the bed making you'll be doing. Then we'll go with that data file! Hey, you add a one and two zeros to that or we walk! You're going to do his laundry? I've got to find a way to escape.
        </v-card-text>
      </div>
    </v-expand-transition>
  </v-card>
</VCol>

<VCol :cols="20">
    <v-card
    class="mx-auto"
    max-width="344"
  >
    <v-img
      src="@/assets/imagem3.jpeg"
      height="200px"
      cover
    ></v-img>

    <v-card-title>
      art #1
    </v-card-title>

    <v-card-subtitle>
      1,000 miles of wonder
    </v-card-subtitle>

    <v-card-actions>
      <v-btn
        color="#711DB0"
        variant="text"
      >
        Explore
      </v-btn>

      <v-spacer></v-spacer>

      <v-btn
        :icon="show2 ? 'mdi-chevron-up' : 'mdi-chevron-down'"
        @click="show2 = !show2"
      ></v-btn>
    </v-card-actions>

    <v-expand-transition>
      <div v-show="show2">
        <v-divider></v-divider>

        <v-card-text>
          I'm a thing. But, like most politicians, he promised more than he could deliver. You won't have time for sleeping, soldier, not with all the bed making you'll be doing. Then we'll go with that data file! Hey, you add a one and two zeros to that or we walk! You're going to do his laundry? I've got to find a way to escape.
        </v-card-text>
      </div>
    </v-expand-transition>
  </v-card>
</VCol>
</v-row>

</v-container>
</template>

<script>

export default {
  name: 'HelloWorld',
  data: () => ({
      show: false,
      show2:false
})
}
</script>

<style>
  
</style>

