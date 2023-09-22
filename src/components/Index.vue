<script setup>

</script>

<template>
  <div class="maincss">
    <div class="indexcss">
      <div>
        <img class="indexlogo" src="./logos/png/logowhite.png" alt="Logo">
      </div>
      <div class="indexname">
        <p>Web Developer</p>
        <h1>Felipe Hanitzsch</h1>
        <p>Welcome to my portfolio, feel free to take a look on my <a href="https://github.com/hanitf">Github</a> page and
          my <a href="https://www.linkedin.com/in/felipe-hanitzsch-33b625122/">
            Linkedin</a>, do not resitate to contact me!</p>
      </div>
    </div>
    <div class="aboutme" id="aboutme">
      <h1>About me</h1>
      <p>I have been passionate about technology since I was a child, I had experience with IT support in video production
        companies, where I had my first contact with software development, covering the need to maintain the rendering of
        images on farm servers, I currently work in the logistics area, and I'm looking for my first experience as a web
        developer (Front-end), I've completed several courses in the area, highlighting the Ironhack bootcamp, where we
        worked with the main web development technologies, HTML5, CSS3 and JavaScript, always connected by Vue.js, the
        course guided us through challenges with API's, Data bases like Supabase, and development of interactive and
        complex web applications. Don't hesitate to visit my Portfolio or my GitHub.</p>
    </div>
    <div class="skills" id="skills">
      <h1>Skills</h1>
      <img src="./logos/skillslogo.png" alt="Skills logo" class="skillslogo">
      <p>Web developer in Html, CSS, Javascript and Vue.js</p>
      <p>Welcome to my portfolio, feel free to take a look on my <a href="https://github.com/hanitf">Github</a> page and
        my <a href="https://www.linkedin.com/in/felipe-hanitzsch-33b625122/">
          Linkedin</a>, do not resitate to contact me!</p>
    </div>
    <div class="projects" id="projects">
      <h1>Projects</h1>
      <iframe src="https://itodohanitzsch.netlify.app/" frameborder="0" height="300" width="300"></iframe>
      <iframe src="https://itodohanitzsch.netlify.app/" frameborder="0" height="300" width="300"></iframe>
      <iframe src="https://itodohanitzsch.netlify.app/" frameborder="0" height="300" width="300"></iframe>
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
  padding-top: 150px;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

.indexname {
  padding-left: 50px;
}

.indexname,
a {
  text-decoration: none;
  color: black;
}

.indexlogo {
  width: 170px;
  height: 150px;
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

</style>