<!-- jumbotron -->
<script>
export default {
  name: 'AppHero',
  data(){
    return{
      titleJumbo: 'Heading'
    }
  }

}
</script>

<template>
  <div class="jumbo">
    
    <h1>{{ titleJumbo }}</h1>
    <h2>Subheading</h2>
    <button>CALL TO ACTION</button>
  </div>

</template>

<style>
  body{
    
  }
  
  .jumbo{
    height: 400px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    color: white;
    background-image: url('https://mdbcdn.b-cdn.net/img/new/slides/041.webp');
  }

  
  .jumbo *{
    margin: 10px;
  }
  
  .jumbo h1{
    font-size: 45px;
  }
  
  .jumbo h2{
    font-size: 25px;
  }
  
  .jumbo button {
    background-color: transparent;
    background-repeat: no-repeat;
    cursor: pointer;
    overflow: hidden;
    outline: none;
    color: white;
    border: 1px white solid;
    border-radius: 5px;
    font-size: 16px;
    padding: 20px;
    transition: 0.5s;
    cursor: pointer;
  }
  
  .jumbo h1:hover, .jumbo h2:hover {
    text-decoration: underline;
  }
  
  .jumbo button:hover {
    transition: 0.5s;
    transform: scale(1.1);
  }

</style>