<template>
  <div id="app">
    <v-app>
      <v-app-bar app dark>
        <v-toolbar-title>Auth example</v-toolbar-title>
        <v-spacer />
        <v-btn icon nuxt href="/"><v-icon>home</v-icon></v-btn>
        <v-btn icon nuxt href="/login"><v-icon>person</v-icon></v-btn>
      </v-app-bar>
      <v-content>
        <v-container fluid>
          <nuxt/>
        </v-container>
      </v-content>
    </v-app>
  </div>
</template>