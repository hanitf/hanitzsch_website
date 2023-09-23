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
      <div class="projectframe">
      <iframe src="https://itodohanitzsch.netlify.app/" frameborder="0" height="300" width="500"></iframe>
      <iframe src="https://itodohanitzsch.netlify.app/" frameborder="0" height="300" width="500"></iframe>
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
  padding-top: 110px;
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

.projectframe{
display: flex;
flex-direction: row;
}


</style>