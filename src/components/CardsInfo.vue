
<template>
  <v-container fluid>
    <v-row>
  <div>
    <v-hover v-slot="{ isHovering, props }">
      <v-card
        class="mx-auto"
        color="grey-lighten-4"
        max-width="400"
        v-bind="props"
      >
        <v-img
          :aspect-ratio="10/9"
          cover
          src="https://res.cloudinary.com/practicaldev/image/fetch/s--L71__yWO--/c_imagga_scale,f_auto,fl_progressive,h_900,q_auto,w_1600/https://dev-to-uploads.s3.amazonaws.com/i/z74oqos1984w5g5ah0i9.jpeg"
        >
          <v-expand-transition>
            <div 
              v-if="isHovering"
              class="d-flex transition-fast-in-fast-out bg-red-darken-2 v-card--reveal text-h2"
              style="height: 100%;"
            >
           UI/UX design
              
            </div>
          </v-expand-transition>
        </v-img>

        <v-card-text class="pt-6">
         
          <h3 class="text-h4 font-weight-light text-red mb-2">
            About:
          </h3>

          <div class="font-weight-light text-h6 mb-2">
            This involves creating the user interface and user experience of a website or web application. Creating a visually appealing and responsive website for users.<br>
            
          </div>
        </v-card-text>
      </v-card>
    </v-hover>
  </div>

  <div style="margin-left: 50px;">
    <v-hover v-slot="{ isHovering, props }">
      <v-card
        class="mx-auto"
        color="grey-lighten-4"
        max-width="400"
        v-bind="props"
      >
        <v-img
          :aspect-ratio="10/9"
          cover
          src="https://assets.website-files.com/60d251a34163cf29e1220806/63742e4e397f173624ab462e_355-3557482_flutter-logo-png-transparent-png.png"
        >
          <v-expand-transition>
            <div
              v-if="isHovering"
              class="d-flex transition-fast-in-fast-out bg-red-darken-2 v-card--reveal text-h2"
              style="height: 100%;"
            >
              Mobile apps
            </div>
          </v-expand-transition>
        </v-img>

        <v-card-text class="pt-6">

          <h3 class="text-h4 font-weight-light text-red mb-2">
            About:
          </h3>

          <div class="font-weight-light text-h6 mb-2">
            Looking for a way to take your business to the next level? Our mobile app development services can help you achieve just that!
          </div>
        </v-card-text>
      </v-card>
    </v-hover>
  </div>

  <div style="margin-left: 50px;">
    <v-hover v-slot="{ isHovering, props }">
      <v-card
        class="mx-auto"
        color="grey-lighten-4"
        max-width="400"
        v-bind="props"
      >
        <v-img
          :aspect-ratio="10/9"
          cover
          src="https://res.cloudinary.com/practicaldev/image/fetch/s--gBj1m14t--/c_imagga_scale,f_auto,fl_progressive,h_900,q_auto,w_1600/https://cdn-images-1.medium.com/max/1200/1%2AaBsgPiEeOE5lLoippRm7BA.png"
        >
          <v-expand-transition>
            <div
              v-if="isHovering"
              class="d-flex transition-fast-in-fast-out bg-red-darken-2 v-card--reveal text-h2"
              style="height: 100%;"
            >
              Desktop apps
            </div>
          </v-expand-transition>
        </v-img>

        <v-card-text class="pt-6">

          <h3 class="text-h4 font-weight-light text-red mb-2">
            About:
          </h3>

          <div class="font-weight-light text-h6 mb-2">
            Looking to build desktop applications that can help your business operations or enhance your user's experience? meet our professional desktop products
          </div>
        </v-card-text>
      </v-card>
    </v-hover>
  </div>
</v-row>
</v-container>
</template>

<script>

export default {
  name: 'HelloWorld',

}
</script>

<style>
  .v-card--reveal {
    align-items: center;
    bottom: 0;
    justify-content: center;
    opacity: .9;
    position: absolute;
    width: 100%;
  }
</style>

