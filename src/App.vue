<template>
  <v-app>
    <v-app-bar app>
      <v-toolbar-title class="headline text-uppercase">
        <span>Misty Morning</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn text href="https://github.com/vuetifyjs/vuetify/releases/latest" target="_blank">
        <span class="mr-2">Profile</span>
      </v-btn>
    </v-app-bar>

    <v-content>
      <Frontpage />
    </v-content>
  </v-app>
</template>

<script>
import Frontpage from './components/Frontpage'

export default {
  name: 'App',
  components: {
    Frontpage
  },
  data: () => ({
    //
  })
}
</script>
