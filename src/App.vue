<template>
  <v-app>
    <v-main>
      <v-container fluid fill-height>
        <v-row justify="center">
          <v-col md="3" class="px-10">
              <h3>Vuetify Field <br><br> </h3>
              <v-text-field
                  label="Regular"
              ></v-text-field>
          </v-col>

          <v-col md="3" class="px-10">
              <h3>Vuetify field with Tailwind-like styles</h3>
              <v-text-field
                  label="Regular"
                  class="custom-style"
              ></v-text-field>
          </v-col>

        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
export default {
  name: 'App',

  components: {},

  data: () => ({
    //
  }),
};
</script>
