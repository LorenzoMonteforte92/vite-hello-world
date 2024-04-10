<script>
  import AppTitle from './components/AppTitle.vue';
  import AppJumboTron from './components/AppJumboTron.vue';

 export default {
  components: { 
    AppTitle,
    AppJumboTron
  
  }
 }

</script>

<template>
  <div class="container">
    <AppTitle></AppTitle>
    <AppJumboTron></AppJumboTron>
  </div>
  
</template>

<style>
.container{
    margin: 0 auto;
    width: 1280px;
    height: 600px;
    display: flex;
    flex-direction: column;
}

body{
  background-color: #2F3B6F;
}
</style>
