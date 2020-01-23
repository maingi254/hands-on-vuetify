<template>
  <v-app>
    <v-app-bar
    app
    color="primary"
    >
    </v-app-bar>
    <v-content>
      <checkout/>
    </v-content>
    
  </v-app>
</template>

<script>
import checkout from './components/checkout'
export default {
  name:'App',
components:{
  checkout
}
}
</script>

<style>

</style>
