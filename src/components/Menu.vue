<script setup>

</script>

<template>
  <nav class="navelements">

    <div class="leftulmenu">

    </div>



    <div class="rightulmenu">
      <div>
        <a href="https://github.com/hanitf">
          <img class="logogithub" src="./logos/githublogo.png" alt="">
        </a>
      </div>
      <div>
        <a href="https://www.linkedin.com/in/felipe-hanitzsch-33b625122/">
        <img class="logolinkedin" src="./logos/linkedinlogo.png" alt="">
        </a>
      </div>
      <div>
        <a href="mailto:felipe@hanitzsch.me">
        <img class="logomail" src="./logos/maillogo.png" alt="">
        </a>
      </div>
      <div>
        <a download="src\resume\FELIPE_HANITZSCH_CV.pdf">
        <button class="buttonresume">Resume</button>
        </a>
      </div>
    </div>

  </nav>
</template>

<style scoped>
.navelements {
  list-style: none;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  padding-top: 30px;

}


.leftulmenu {
  padding-left: 200px;
  width: 350px;
  color: aliceblue;
  list-style: none;
  display: flex;
  justify-content: space-around;
  font-size: 19px;
  font-family: Poppins;
  letter-spacing: 1.5px;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

.rightulmenu {
  padding-right: 180px;
  width: 300px;
  color: aliceblue;
  list-style: none;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
}

a {
  text-decoration: none;
  color: rgb(142, 140, 140);
}

.buttonresume {

  position: relative;
  display: inline-block;
  margin: 12px;
  padding: 5px 30px;
  text-align: center;
  font-size: 15px;
  letter-spacing: 1px;
  text-decoration: none;
  color: #000000;
  background: transparent;
  cursor: pointer;
  transition: ease-out 0.5s;
  border: 2px solid #000000;
  border-radius: 10px;
  box-shadow: inset 0 0 0 0 #000000;
}

.buttonresume:hover {
  color: white;
  box-shadow: inset 0 -100px 0 0 #c9c5d4;
}

.buttoresume:active {
  transform: scale(0.9);
}

.logogithub {
  padding-top: 9px;
  width: 35px;
}

.logolinkedin {
  padding-top: 6.3px;
  width: 40px;
}
.logomail {
  padding-top: 6.3px;
  width: 40px;
}

</style>