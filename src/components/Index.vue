<script setup>

</script>

<template>
  <div class="maincss">
    <div class="indexcss">
      <div>
        <img class="indexlogo" src="./logos/png/logowhite.png" alt="Logo">
      </div>
      <div class="indexname">
        <h1>Felipe Hanitzsch</h1>
        <p>Welcome to my portfolio, feel free to take a look on my <a href="https://github.com/hanitf">Github</a> page and
          my <a href="https://www.linkedin.com/in/felipe-hanitzsch-33b625122/">
            Linkedin</a>, do not resitate to contact me!</p>
      </div>
    </div>
    <div class="aboutme" id="aboutme">
      <h1>About me</h1>
      <img src="./logos/680-it-developer.gif" alt="About me logo" class="aboutmelogo">
      <p>I have been passionate about technology since I was a child, I had experience with IT support in video production
        companies, where I had my first contact with software development, covering the need to maintain the rendering of
        images on farm servers, I currently work in the logistics area, and I'm looking for my first experience as a web
        developer (Front-end), I've completed several courses in the area, highlighting the Ironhack bootcamp, where we
        worked with the main web development technologies.</p>
    </div>
    <div class="skills" id="skills">
      <h1>Skills</h1>
      <img src="./logos/skillslogo.png" alt="Skills logo" class="skillslogo">
      <p>Web developer in Html, CSS, Javascript and Vue.js</p>
      <p>Ironhack certified in HTML5, CSS3 and JavaScript, always connected by Vue.js, the
        course guided us through challenges with API's, Data bases like Supabase, and development of interactive and
        complex web applications.</p>
    </div>
    
    <div class="projects" id="projects">
      <h1 class="projectname">Projects</h1>
      <div class="projectlinks">
        <button class="buttonresume"><a href="https://itodohanitzsch.netlify.app/">Itodo - To do List</a></button>
        <button class="buttonresume"><a href="https://hanitf.netlify.app/">Replication from a website</a></button>
      </div>
      <div class="projectframe">
      <iframe src="https://itodohanitzsch.netlify.app/" frameborder="0" height="300" width="500"></iframe>
      <iframe src="https://hanitf.netlify.app/" frameborder="0" height="300" width="500"></iframe>
    </div>
    </div>
  </div>
</template>

<style scoped>
.maincss {
  max-width: 1000px;
  margin: 0 auto;
}

.indexcss {
  display: flex;
  flex-direction: row;
  font-family: 'Segoe UI', Tahoma, Verdana, sans-serif;
  align-items: center;
  height: 900px;
}

.indexname {
  padding-left: 50px;
  font-size: 23px;
}

.indexname,
a {
  text-decoration: none;
  color: black;
}

.indexlogo {
  width: 370px;
  height: 350px;
  border: 3px solid #ccc;
  border-radius: 50%;
  background: #eee;
  margin: auto;
  padding: 15px 10px;
}

.skillslogo{
  width: 190px;
  height: 170px;
}

.aboutmelogo{
  width: 390px;
  height: 370px;
}

.aboutme{
  display: flex;
  height: 900px;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  font-size: 25px;
  word-spacing: 2px;
}
.skills{
  display: flex;
  height: 900px;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  font-size: 25px;
  word-spacing: 2px;
}

.projects{ 
  display: flex;
  height: 900px;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}

.projectname{
  padding-bottom: 20px;
}

.projectframe{
display: flex;
flex-direction: row;
}

.projectlinks{
  display: flex;
flex-direction: row;
justify-content: space-between;
width: 750px;
padding-bottom: 20px;
font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
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

/* Styles for screens with a maximum width of 950px */
@media screen and (max-width: 950px) {
  .maincss {
    max-width: 100%; /* Adjusted for screens up to 950px */
    margin: 0 auto;
  }

  .indexcss {
    display: flex;
    flex-direction: column; /* Adjusted for screens up to 950px */
    font-family: 'Segoe UI', Tahoma, Verdana, sans-serif;
    align-items: center;
    height: auto; /* Adjusted for screens up to 950px */
  }

  .indexname {
    padding-left: 20px; /* Adjusted for screens up to 950px */
    font-size: 20px; /* Adjusted for screens up to 950px */
  }

  .indexname,
  a {
    text-decoration: none;
    color: black;
  }

  .indexlogo {
    width: 250px; /* Adjusted for screens up to 950px */
    height: 250px; /* Adjusted for screens up to 950px */
    border: 3px solid #ccc;
    border-radius: 50%;
    background: #eee;
    margin: auto;
    padding: 15px 10px; /* Adjusted for screens up to 950px */
  }

  .skillslogo {
    width: 150px;
    height: 135px;
  }

  .aboutmelogo {
    width: 300px; /* Adjusted for screens up to 950px */
    height: 280px; /* Adjusted for screens up to 950px */
  }

  .aboutme,
  .skills,
  .projects {
    display: flex;
    height: auto; /* Adjusted for screens up to 950px */
    align-items: center;
    flex-direction: column;
    justify-content: center;
    font-size: 18px; /* Adjusted for screens up to 950px */
    word-spacing: 2px;
  }

  .projects {
    padding-top: 20px; /* Adjusted for screens up to 950px */
  }

  .projectname {
    padding-bottom: 10px; /* Adjusted for screens up to 950px */
  }

  .projectframe {
    display: flex;
    flex-direction: column; /* Adjusted for screens up to 950px */
  }

  .projectlinks {
    display: flex;
    flex-direction: column; /* Adjusted for screens up to 950px */
    width: 100%; /* Adjusted for screens up to 950px */
    padding-bottom: 10px; /* Adjusted for screens up to 950px */
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
  }

  .buttonresume {
    position: relative;
    display: inline-block;
    margin: 12px;
    padding: 5px 20px; /* Adjusted for screens up to 950px */
    text-align: center;
    font-size: 12px; /* Adjusted for screens up to 950px */
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
}

/* Styles for screens with a maximum width of 1200px */
@media screen and (max-width: 1200px) {
  .maincss {
    max-width: 1000px;
    margin: 0 auto;
  }

  .indexcss {
    display: flex;
    flex-direction: row;
    font-family: 'Segoe UI', Tahoma, Verdana, sans-serif;
    align-items: center;
    height: 900px;
  }

  .indexname {
    padding-left: 50px;
    font-size: 23px;
  }

  .indexname,
  a {
    text-decoration: none;
    color: black;
  }

  .indexlogo {
    width: 370px;
    height: 350px;
    border: 3px solid #ccc;
    border-radius: 50%;
    background: #eee;
    margin: auto;
    padding: 15px 10px;
  }

  .skillslogo {
    width: 190px;
    height: 170px;
  }

  .aboutmelogo {
    width: 390px;
    height: 370px;
  }

  .aboutme,
  .skills,
  .projects {
    display: flex;
    height: 900px;
    align-items: center;
    flex-direction: column;
    justify-content: center;
    font-size: 25px;
    word-spacing: 2px;
  }

  .projects {
    padding-top: 20px;
  }

  .projectname {
    padding-bottom: 20px;
  }

  .projectframe {
    display: flex;
    flex-direction: row;
  }

  .projectlinks {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    width: 750px;
    padding-bottom: 20px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
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
}




</style>