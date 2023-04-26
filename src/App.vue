<!-- Create un nuovo progetto utilizzando Vite. -->
<!-- Create e utilizzate un componente `AppTitle`, il quale contiene un titolo che recita “La mia prima app con Vite!” -->

<!-- **Bonus:** -->
<!-- Creare un secondo componente AppHero, che visualizza un jumbotron. -->

<script>
import AppTitle from './components/AppTitle.vue'
import AppHero from './components/AppHero.vue'

export default {
  name: 'App',
  components: {
    AppTitle,
    AppHero

  },
  data(){
    return{
      testString: 'Hello World!'
    }
  }

}
</script>

<template>
  <AppHero/>
  <h1>{{ testString }}</h1>
  <AppTitle/>
</template>

<style scoped>
  h1{
    color: red;
  }
</style>
