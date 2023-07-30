<script setup>
import Index from './components/Index.vue'
import Projects from './components/Projects.vue';
import Menu from './components/Menu.vue';
import Footer from './components/Footer.vue';
import Contact from './components/Contact.vue';
</script>

<template>
  <body>
    
    <div class="divmenu">
      <Menu></Menu>
    </div>

    <div class="divaboutme">
      <Index></Index>
    </div>


    <div class="divfooter">
      <Footer></Footer>
   </div>
  
  </body>

</template>

<style scoped>

body{
  background-color: rgb(255, 255, 255);
}



</style>
