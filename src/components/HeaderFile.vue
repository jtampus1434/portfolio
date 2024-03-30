<!-- <template>
    <nav class="navbar navbar-expand-lg navbar-dark sticky-top" style="background-color: #3a1772;">
      <div class="container-fluid">
        <router-link to="/" class="navbar-brand">
          <img src="profile-user.png" alt="Portfolio Icon" width="30" height="30" class="me-2">
          <span class="fs-5">Jonathan Ivan Tam</span>
        </router-link>
  
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
  
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ms-auto">
            <li class="nav-item">
              <router-link to="/about" class="nav-link">About</router-link>
            </li>
            Add more navigation links as needed
  
          <div class="social-links">
            <a href="https://web.facebook.com/reynaldo.1102" target="_blank" class="text-white me-3">
              <img src="facebook.png" width="30px" alt="Facebook" title="Facebook">
            </a>
            <a href="mailto:andalesr11@gmail.com" target="_blank" class="text-white me-3">
              <img src="gmail.png" width="30px" alt="Gmail" title="Gmail">
            </a>
            <a href="https://www.tiktok.com/@kil9648?_t=8l6fHAbfHwl&_r=1" target="_blank" class="text-white">
              <img src="tik-tok.png" width="30px" alt="TikTok" title="TikTok">
            </a>
          </div>
        </div>
      </div>
    </nav>
  </template>
  
  <script>
  export default {
    // Add any necessary logic here
  }
  </script>
  
  <style scoped>
  .navbar-brand img {
    filter: brightness(0) invert(1);
  }
  .social-links {
    display: flex;
    align-items: center;
  }
  .social-links a {
    text-decoration: none;
    color: #fff;
  }
  .social-links img {
    margin-right: 10px;
  }
  </style>
   -->

   <template>
    <header class="header sticky-top">
      <div class="container">
        <div class="logo">
          <img src="profile-user.png" alt="Logo">
        </div>
        <nav  class="nav">
          <ul class="nav-list">
            <li class="nav-item"><a href="#home" class="nav-link">About</a></li>
            <li class="nav-item"><a href="#skills" class="nav-link">Skills</a></li>
            <li class="nav-item"><a href="#contact" class="nav-link">Reach Me</a></li>
          </ul>
        </nav>
      </div>
    </header>
  </template>
  
  <style scoped>
  .header {
    background-color: #41456b;
    color: #fff;
    padding: 20px 0;
  }
  
  .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  
  .logo img {
    max-width: 100px;
  }
  
  .nav {
    flex-grow: 1;
  }
  
  .nav-list {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
  }
  
  .nav-item {
    margin-right: 20px;
  }
  
  .nav-link {
    color: #fff;
    text-decoration: none;
    font-size: 18px;
  }
  
  .nav-link:hover {
    text-decoration: underline;
  }
  </style>