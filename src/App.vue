<template>
  <v-app id="app">
    <nav-bar></nav-bar>

    <v-content>
      <v-container>
        <home></home>
      </v-container>
    </v-content>

  </v-app>
</template>

<script>
import navbar from './components/navbar'
import home from './components/home'
export default {
  name: 'App',
  components: {
    navbar,
    home
  }
}
</script>