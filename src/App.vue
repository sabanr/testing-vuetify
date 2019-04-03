<template>
  <v-app class="grey lighten-4">
    <nav-bar></nav-bar>
    <v-content>
      <router-view></router-view>
    </v-content>
  </v-app>
</template>

<script>
import NavBar from '@/components/NavBar.vue'

export default {
  name: 'App',
  components: {
    NavBar
  },
  data () {
    return {
      //
    }
  }
}
</script>
