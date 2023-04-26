<!-- Create un nuovo progetto utilizzando Vite. -->
<!-- Create e utilizzate un componente `AppTitle`, il quale contiene un titolo che recita “La mia prima app con Vite!” -->

<script>
import AppTitle from './components/AppTitle.vue'

export default {
  name: 'App',
  components: {
    AppTitle

  },
  data(){
    return{
      testString: 'Hello World!'
    }
  }
  
}
</script>

<template>
  <h1>{{ testString }}</h1>
  <AppTitle/>

</template>

<style>

</style>
