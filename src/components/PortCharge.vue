<!-- ProjectsLayout.vue -->
<template>
    <div id="projects" class="line"></div>
    <div class="projects-layout">
      <div class="container">
        <h2 class="section-title">Projects</h2>
        <div class="projects">
          <div class="project">
            <img src="Calculator.png" alt="Project 1" class="project-image">
            <div class="project-details">
              <h3 class="project-title">Calculator</h3>
              <p class="project-description">JAVA CALCULATOR ON TEXTPAD 9</p>
              <a href="https://github.com/Atling123/Calculator" class="project-link">View Project</a>
            </div>
          </div>
          <div class="project">
            <img src="Spotify.jpg" alt="Project 2" class="project-image">
            <div class="project-details">
              <h3 class="project-title">SPOTIFY API</h3>
              <p class="project-description">App Creation using RESTFUL API</p>
              <a href="#" class="project-link">View Project</a>
            </div>
          </div>
          <div class="project">
            <img src="Car.jpg" alt="Project 2" class="project-image">
            <div class="project-details">
              <h3 class="project-title">Automobile Services Booking System</h3>
              <p class="project-description">We have created a Web Application for Automobile Services Booking System</p>
              <a href="https://github.com/LanceTheWeakProgrammer/Booking" class="project-link">View Project</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <style scoped>
.line {
  height: 1px;
  background-color: rgb(239, 228, 228); /* Change color as needed */
  margin: 20px 100; /* Adjust spacing as needed */
}

  .projects-layout {
    padding: 50px 0;
    background-color: #989696;
  }
  
  .container {
    max-width: 1200px;
    margin: 0 auto;
  }
  
  .section-title {
    font-size: 32px;
    font-weight: bold;
    margin-bottom: 30px;
  }
  
  .projects {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    grid-gap: 30px;
  }
  
  .project {
    border: 1px solid #ddd;
    padding: 20px;
    background-color: #bdbaba;
  }
  
  .project-image {
    width: 100%;
    height: auto;
    margin-bottom: 15px;
  }
  
  .project-title {
    font-size: 24px;
    margin-bottom: 10px;
  }
  
  .project-description {
    font-size: 16px;
    margin-bottom: 15px;
  }
  
  .project-link {
    display: inline-block;
    padding: 5px 10px;
    background-color: #333;
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
  }
  
  .project-link:hover {
    background-color: #555;
  }
  </style>
  