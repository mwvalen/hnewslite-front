<template>
  <v-app>
    <v-toolbar app>
      <router-link to='/' class='link'>
      <v-toolbar-title class="headline text-uppercase">
        <span>HackerNews</span>
        <span class="font-weight-light">LITE</span>
      </v-toolbar-title>
      </router-link>
      <v-spacer></v-spacer>
        <router-link to='/about' class='link'>
          <span class="mr-2">About</span>
        </router-link>
    </v-toolbar>

    <v-content>
      <router-view/>
    </v-content>
  </v-app>
</template>

<script>

export default {
  name: 'App',
  data () {
    return {
      //
    }
  }
}
</script>

<style scoped>
  .link {
    color: black;
    text-decoration: none;
  }
</style>

