<template>
  <v-item-group mandatory>
    <v-container>
      <v-row>
        <v-col
          v-for="n in 2"
          :key="n"
          cols="12"
          md="6"
        >
          <v-item v-slot="{ isSelected, toggle }">
            <v-card
              :color="isSelected ? 'primary' : ''"
              class="d-flex align-center"
              dark
              height="200"
              @click="toggle"
            >
              <v-scroll-y-transition>
                <div
                  class="text-h3 flex-grow-1 text-center"
                >
                  <!-- {{ isSelected ? 'Offering Pool' : 'Requesting Pool' }} -->
                  {dfdsfds}
                </div>
              </v-scroll-y-transition>
            </v-card>
          </v-item>
        </v-col>
      </v-row>
    </v-container>
  </v-item-group>
</template>
<script>

</script>
