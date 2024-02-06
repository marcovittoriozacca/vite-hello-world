<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';

  export default{
    components:{
      AppTitle,
      AppHero,
    }
  }

</script>



<template>
  
  <AppTitle></AppTitle>

  <AppHero></AppHero>

</template>



<style>
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  html{
      font-family: sans-serif;
      background-color: rgb(61, 61, 61);
  }

</style>
