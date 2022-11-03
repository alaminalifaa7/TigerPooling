<template>
  <v-app>
     <v-app-bar color="white-2">
      <v-app-bar-nav-icon> <v-icon icon="fas fa-plus" /> </v-app-bar-nav-icon>
      <v-app-bar-title>  <v-icon large color="orange-darken-2" icon="mdi-car"></v-icon> <v-icon large color="orange-darken-2" icon="mdi-motorbike"></v-icon> TigerPooling</v-app-bar-title> 
    
     </v-app-bar>
    <v-main>
     <choose-pool/>
     <pool-form />
    </v-main>
  </v-app>
</template>

<script>
import ChoosePool from "./components/ChoosePool.vue"
import PoolForm from "./components/PoolForm.vue"

export default {
  components: {
    ChoosePool,PoolForm
  },
  setup() {
    // ...
  }
}
</script>
