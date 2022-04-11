<template>
    <v-app-bar dense clipped-left clipped-right color="indigo darken-2" dark app>
      <v-toolbar-title  class="headline text-uppercase">
        <v-icon>fa-facebook-square</v-icon>
      </v-toolbar-title>
      <v-toolbar-items>
        <v-btn text class="questrial text-none font-weight-bold">Home</v-btn>
        <v-btn text class="questrial text-none font-weight-bold">Find Friends</v-btn>
      </v-toolbar-items>
      <v-spacer></v-spacer>
        <!-- <v-text-field  append-icon="mdi-magnify" class="mt-8" label="Search" rounded solo light></v-text-field> -->
      <v-spacer></v-spacer>
      <v-toolbar-items>
        <v-btn icon><v-icon color="black lighten-4">mdi-account-multiple</v-icon></v-btn>
        <v-btn icon><v-icon color="black lighten-4">mdi-message</v-icon></v-btn>
        <v-btn icon><v-icon color="black lighten-4">mdi-bell</v-icon></v-btn>
        <v-btn icon><v-icon color="black lighten-4">mdi-help-box</v-icon></v-btn>
        
        <v-avatar class="mt-2" :size="30">
          <img src="https://cdn.quasar.dev/img/boy-avatar.png" alt="avatar">
        </v-avatar>
      </v-toolbar-items>
    </v-app-bar>
</template>

<script>
export default {

}
</script>


