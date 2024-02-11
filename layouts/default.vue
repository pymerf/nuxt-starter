<template>
  <v-app>
    <v-app-bar color="indigo-darken-4">
      <template v-slot:prepend>
        <v-btn to="/" icon="mdi-home"></v-btn>
      </template>
      <v-app-bar-title>Nuxt Starter</v-app-bar-title>

      <v-btn to="/users">Users</v-btn>
      <v-btn to="/signup">SignUp</v-btn>
      <v-btn to="/signin">SignIn</v-btn>
    </v-app-bar>
    <v-main>
      <v-container class="pt-8">
        <slot />
      </v-container>
    </v-main>
  </v-app>
</template>
