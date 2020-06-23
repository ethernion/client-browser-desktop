<template>
  <v-container class="d-flex pa-0 align-center justify-center fill-height">
    <v-card outlined tile width="400">
      <v-card-title>
        Login
      </v-card-title>
      <v-card-text>
        <v-text-field prepend-icon="mdi-email" type="email" label="E-mail" autocomplete="off"></v-text-field>
        <v-text-field prepend-icon="mdi-lock" type="password" label="Passwort" autocomplete="off"></v-text-field>
      </v-card-text>
      <v-card-actions>
        <v-btn depressed class="rounded-0" color="primary">
          Submit
        </v-btn>
        <v-spacer></v-spacer>
        <nuxt-link tag="span" to="/signup">
          <v-btn class="rounded-0 px-2" text>
            Sign Up
          </v-btn>
        </nuxt-link>
      </v-card-actions>
    </v-card>
  </v-container>
</template>

<script>
export default {

}
</script>

<style>

</style>