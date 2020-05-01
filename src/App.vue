<template>
<v-app>
  <v-app-bar app clipped-left dark color="red">
    <v-toolbar-title>VuePong</v-toolbar-title>
  </v-app-bar>
  <v-navigation-drawer app clipped class="green lighten-1"> </v-navigation-drawer>
    <v-content class="brown noOverflow">
      <router-view />
    </v-content>
</v-app>
</template>