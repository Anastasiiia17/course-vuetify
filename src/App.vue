<template>
  <v-app>
      <v-app-bar density="compact" absolute>
        <v-app-bar-title>HangZen</v-app-bar-title>
  
        <v-spacer></v-spacer>
  
        <v-btn text>Create</v-btn>
  
        <v-btn class="mr-3" text>Help</v-btn>
  
        <v-divider inset vertical></v-divider>
  
        <v-btn
          class="mr-4 ml-5"
          color="primary"
          plain
        >
          <v-icon left icon="mdi-handshake-outline"></v-icon>
  
          <span>John Leider</span>
        </v-btn>
      </v-app-bar>

  </v-app>
</template>

<script>
export default {
  name: 'App',

  
}
</script>
