<script setup>
import Aboutme from './components/Aboutme.vue';
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
      <Aboutme></Aboutme>
    </div>

    <div class="divportfolio">
      <Projects></Projects>
    </div>

    <div class="divcontact">
      <Contact></Contact>
    </div>

    <div class="divfooter">
      <Footer></Footer>
   </div>
  
  </body>

</template>

<style scoped>

body{
  background-color: rgb(138, 37, 37);
}


</style>
