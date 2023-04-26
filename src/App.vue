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
  <div class="container-body">
    <h1>{{ testString }}</h1>
    <AppTitle/>
  </div>
</template>

<style scoped>
  h1{
    color: white;
  }

  .container-body{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    margin-top: 40px;
  }

  .container-body *{
    margin: 30px;
  }

  </style>
