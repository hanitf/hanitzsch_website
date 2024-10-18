<script setup>

</script>

<template>
  <div class="mainmenu">
    <div>
      <ul class="leftulmenu">
      <a href="">
<li>Home</li>
</a>
<a href="#aboutme">
<li>About me</li>
</a>
<a href="#skills">
<li>Skills</li>
</a>
<a href="#projects">
<li>Projects</li>
</a>
</ul>    
</div>
    <div class="rightulmenu">
      <div class="spaceimg">
        <a href="https://github.com/hanitf">
          <img class="logogithub" src="./logos/githublogo.png" alt="">
        </a>
      </div>
      <div class="spaceimg">
        <a href="https://www.linkedin.com/in/felipe-hanitzsch-33b625122/">
        <img class="logolinkedin" src="./logos/linkedinlogo.png" alt="">
        </a>
      </div>
      <div class="spaceimg">
        <a href="mailto:felipe@hanitzsch.me">
        <img class="logomail" src="./logos/maillogo.png" alt="">
        </a>
      </div>
      <div>
        <a href="https://drive.google.com/file/d/1F61z7PyRPhRgM6D-0TLDdkItTFBNFP0M/view?usp=drive_link" target="_blank">
        <button class="buttonresume">Resume</button>
        </a>
      </div>
  </div>
</div>
</template>

<style scoped>

.mainmenu{
  list-style: none;
  display: flex;
  flex-direction: row;
  position: fixed;
  margin: 0 auto;
  justify-content: space-around;
  width: 100%;
  background: rgba(196, 196, 196, 0.664);
  backdrop-filter: blur(15px);
  top: 0;
  left: 0;
  border-bottom: solid 1px rgba(255, 255, 255, 0.452);
  box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
  z-index: 1;
  opacity: 100%;
  border-radius: 10px;
}
.leftulmenu {
  color: rgb(0, 0, 0);
  list-style: none;
  font-size: 19px;
  letter-spacing: 1.5px;
  font-family: 'Segoe UI', Tahoma, Verdana, sans-serif;
  list-style: none;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  width: 500px;
}

.leftulmenu li {
  color: black;
  text-shadow: 0px 8px 16px 0px white;
}

.rightulmenu {
  color: aliceblue;
  list-style: none;
  display: flex;
  flex-direction: row;
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
  padding-left: 10px;
}

.logolinkedin {
  padding-top: 6.3px;
  width: 40px;
}
.logomail {
  padding-top: 6.3px;
  width: 40px;
}

.spaceimg{
  padding-left: 10px;
}

/* Styles for screens with a maximum width of 1200px */
@media screen and (max-width: 1200px) {
  .mainmenu {
    justify-content: center;
    width: 100%;
    border-radius: 0;
    padding: 10px 0;
    position: static;
    backdrop-filter: none;
    box-shadow: none;
    position: fixed;
    border-bottom: solid 1px rgba(255, 255, 255, 0.452);
    box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
    z-index: 1;
    opacity: 100%;
    background: rgba(196, 196, 196, 0.664);
    backdrop-filter: blur(15px);
  }

  .leftulmenu {
    color: rgb(0, 0, 0);
    list-style: none;
    font-size: 16px; /* Adjusted font size for screens up to 1200px */
    letter-spacing: 1.2px; /* Adjusted letter spacing for screens up to 1200px */
    font-family: 'Segoe UI', Tahoma, Verdana, sans-serif;
    list-style: none;
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    width: 100%; /* Adjusted width for screens up to 1200px */
  }

  .leftulmenu li {
    color: black;
    text-shadow: 0px 8px 16px 0px white;
  }

  .rightulmenu {
    color: aliceblue;
    list-style: none;
    display: flex;
    flex-direction: row;
  }

  a {
    text-decoration: none;
    color: rgb(142, 140, 140);
  }

  .buttonresume {
    position: relative;
    display: inline-block;
    margin: 12px;
    padding: 5px 20px; /* Adjusted padding for screens up to 1200px */
    text-align: center;
    font-size: 12px; /* Adjusted font size for screens up to 1200px */
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
    width: 25px; /* Adjusted width for screens up to 1200px */
    padding-left: 10px;
  }

  .logolinkedin {
    padding-top: 6.3px;
    width: 30px; /* Adjusted width for screens up to 1200px */
  }
  .logomail {
    padding-top: 6.3px;
    width: 30px; /* Adjusted width for screens up to 1200px */
  }

  .spaceimg {
    padding-left: 10px;
  }
}

/* Styles for screens with a maximum width of 950px */
@media screen and (max-width: 950px) {
  .mainmenu {
    justify-content: center;
    width: 100%;
    border-radius: 0;
    padding: 10px 0;
    position: static;
    backdrop-filter: none;
    box-shadow: none;
    position: fixed;
    border-bottom: solid 1px rgba(255, 255, 255, 0.452);
    box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
    z-index: 1;
    opacity: 100%;
    background: rgba(196, 196, 196, 0.664);
    backdrop-filter: blur(15px);
  }

  .leftulmenu {
    color: rgb(0, 0, 0);
    list-style: none;
    font-size: 16px; /* Adjusted font size for screens up to 950px */
    letter-spacing: 1.2px; /* Adjusted letter spacing for screens up to 950px */
    font-family: 'Segoe UI', Tahoma, Verdana, sans-serif;
    list-style: none;
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    width: 100%; /* Adjusted width for screens up to 950px */
  }

  .leftulmenu li {
    color: black;
    text-shadow: 0px 8px 16px 0px white;
  }

  .rightulmenu {
    color: aliceblue;
    list-style: none;
    display: flex;
    flex-direction: row;
  }

  a {
    text-decoration: none;
    color: rgb(142, 140, 140);
  }

  .buttonresume {
    position: relative;
    display: inline-block;
    margin: 12px;
    padding: 5px 20px; /* Adjusted padding for screens up to 950px */
    text-align: center;
    font-size: 12px; /* Adjusted font size for screens up to 950px */
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
    width: 25px; /* Adjusted width for screens up to 950px */
    padding-left: 10px;
  }

  .logolinkedin {
    padding-top: 6.3px;
    width: 30px; /* Adjusted width for screens up to 950px */
  }
  .logomail {
    padding-top: 6.3px;
    width: 30px; /* Adjusted width for screens up to 950px */
  }

  .spaceimg {
    padding-left: 10px;
  }
}






</style>
