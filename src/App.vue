<template>
  <v-app>
    <v-app-bar
    app
    color="primary"
    >
    </v-app-bar>
    <v-content>
      <login/>
    </v-content>
    
  </v-app>
</template>

<script>
//import  autocomplete from './components/autocomplete'
//import checkout from './components/checkout'
import login from './components/login'
export default {
  name:'App',
components:{
  //checkout,
  //autocomplete,
  login
}
}
</script>

<style>

</style>
