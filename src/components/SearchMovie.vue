<template>
    <div class="search-movie">
      <v-card
    class="mx-auto"
    color="grey-lighten-3"
    max-width="400"
  >
    <v-card-text>
      <v-text-field
        :loading="loading"
        density="compact"
        variant="solo"
        label="Search templates"
        append-inner-icon="mdi-magnify"
        single-line
        hide-details
        @click:append-inner="onClick"
      ></v-text-field>
    </v-card-text>
  </v-card>
    </div>
  </template>
  
  <script>

  export default {
    
  };
  </script>
  
  <style>

  </style>