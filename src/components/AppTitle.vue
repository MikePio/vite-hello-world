<script>
export default {
  name: 'AppTitle',
  data(){
    return{
      title: 'La mia prima app con Vite!'
    }
  }
}
</script>

<template>
  <h1>{{ title }}</h1>
</template>

<!-- ! Non funziona in quanto la classe h1 scritta in App.vue si sovrappone alla seguente -->
<style scoped>
h1{
    color: aqua;
  }

</style>