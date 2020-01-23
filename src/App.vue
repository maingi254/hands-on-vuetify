<template>
  <v-app>
    <v-app-bar
    app
    color="primary"
    >
    </v-app-bar>
    <v-content>
      <autocomplete/>
    </v-content>
    
  </v-app>
</template>

<script>
import  autocomplete from './components/autocomplete'
//import checkout from './components/checkout'
export default {
  name:'App',
components:{
  //checkout,
  autocomplete
}
}
</script>

<style>

</style>
