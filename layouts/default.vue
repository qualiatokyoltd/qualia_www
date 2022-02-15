<template>
  <v-app dark>

    <v-app-bar :clipped-left="clipped" fixed app style="background-color:rgb(67,150,148)">
      <v-img src="logo.png" contain width="55" height="55"></v-img>
    </v-app-bar>
    <v-main>
      <v-container>
        <Nuxt />
      </v-container>
    </v-main>
    
    <v-footer :absolute="!fixed" app>
      <span>&copy; {{ new Date().getFullYear() }}</span>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  name: 'DefaultLayout',
  data() {
    return {
      
    }
  },
}
</script>
