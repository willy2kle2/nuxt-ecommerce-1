<template>
  <v-app>
    <v-toolbar color="primary" dark>
      <v-container>
        <v-row>
          <v-toolbar-title>{{ title }}</v-toolbar-title>

          <v-spacer></v-spacer>

          <v-toolbar-items>
            <v-btn text>Link 1</v-btn>
            <v-btn text>Link 2</v-btn>
            <v-btn text>Link 3</v-btn>
          </v-toolbar-items>
        </v-row>
      </v-container>
    </v-toolbar>

    <v-content>
      <nuxt/>
    </v-content>

    <v-footer darkd>
      <v-layout>
        <v-card-text class="white--text">
          {{ new Date().getFullYear() }} — <strong>Vuetify</strong>
        </v-card-text>
      </v-layout>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  data() {
    return {
      title: "NUXT ecommerce"
    };
  }
};
</script>
