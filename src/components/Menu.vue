<script setup>

</script>

<template>
  <nav class="navelements">
    
      <div class="leftulmenu">

        <li><a href="">Home</a></li>
        <li><a href="">About me</a></li>
        <li><a href="">Projects</a></li>
        <li><a href="">Contact</a></li>

      </div>
    

    
      <div class="rightulmenu">

        <a href="" class="linkgithub">Github</a>
        <button class="buttonresume" @click="">Resume</button>

      </div>
    
    </nav>
</template>

<style scoped>

.navelements{
 list-style: none;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
}


.leftulmenu {
  padding-left: 300px;
  width: 350px;
  background-color: black;
  color: aliceblue;
  list-style: none;
  display: flex;
  justify-content: space-around;
 
}

.rightulmenu {
  padding-right: 200px;
  width: 300px;
  background-color: black;
  color: aliceblue;
  list-style: none;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
}

a
{
    text-decoration: none; 
    color: white;
}
</style>