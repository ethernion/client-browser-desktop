<template>
  <v-app dark>
    <v-app-bar fixed app>
      <div class="eth-container">
        <h2 class="eth-title">
          Ethernion
        </h2>
      </div>
    </v-app-bar>
    <v-main>
      <v-container class="eth-container fill-height pa-0">
        <nuxt />
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
export default {
  data: () => ({
  })
}
</script>

<style lang="sass">
.eth-container
  width: 900px
  margin: auto

.eth-title
  text-transform: uppercase
  letter-spacing: 5px
  font-weight: 400

.foo
  border-bottom: thin solid rgba(0, 0, 0, 0.12) !important

</style>
