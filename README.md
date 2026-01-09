<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  Personal Portfolio

  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">

<style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Roboto', sans-serif;
    }

    body {
      background: linear-gradient(to bottom, #a8e6cf, #dcedc1);
      color: #2e3d32;
      overflow-x: hidden;
    }

    body::before {
      content: '';
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: transparent url('https://i.ibb.co/mNfPvP7/leaves.png') repeat;
      z-index: -1;
      animation: moveLeaves 200s linear infinite;
    }

    @keyframes moveLeaves {
      0% { background-position: 0 0; }
      100% { background-position: -5000px 2000px; }
    }

    header {
      text-align: center;
      padding: 80px 20px;
      background: rgba(255,255,255,0.5);
      backdrop-filter: blur(5px);
      border-radius: 15px;
      margin: 20px;
    }

    header h1 {
      font-size: 3rem;
      color: #388e3c;
      text-shadow: 0 0 10px #66bb6a, 0 0 20px #2e7d32;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.2rem;
      color: #4e4e4e;
      text-shadow: 0 0 5px #a5d6a7;
      margin-bottom: 10px;
    }

    .profile-pic {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 20px;
      border: 4px solid #ff6ec7;
      box-shadow:
        0 0 15px #ff6ec7,
        0 0 30px #8a2be2,
        0 0 60px rgba(138,43,226,0.8);
      transition: transform 0.4s ease, box-shadow 0.4s ease;
    }

    .profile-pic:hover {
      transform: scale(1.05);
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 20px 0;
    }

    nav a {
      color: #2e3d32;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      max-width: 900px;
      margin: 40px auto;
      padding: 0 20px;
    }

    section h2 {
      text-align: center;
      color: #2e7d32;
      margin-bottom: 30px;
    }

    .about, .projects, .contact {
      background: rgba(255,255,255,0.2);
      padding: 30px;
      border-radius: 15px;
      backdrop-filter: blur(5px);
      margin-bottom: 40px;
    }

    .project {
      text-align: center;
    }

    /* SHIELD ICON STYLES */
    #skills img {
      margin: 10px;
      transition: transform 0.3s ease;
    }

    #skills img:hover {
      transform: scale(1.1);
    }

    .contact a {
      display: inline-block;
      margin: 10px;
      padding: 12px 25px;
      background: #4caf50;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
    }

    footer {
      text-align: center;
      padding: 20px;
    }
  </style>
</head>

<body>

<header>
  <h1>Geramae Rotone</h1>
  <img src="https://uploads.onecompiler.io/44a2gqpwf/44a2vzmbf/1000008761.jpg" class="profile-pic" alt="Profile Picture">
  <p>"Confusion is part of programming"</p>
</header>

<nav>
  <a href="#home">Home</a>
  <a href="#about">About</a>
  <a href="#skills">Skills</a>
  <a href="#contact">Contact</a>
</nav>

<section id="about" class="about">
  <h2>About Me</h2>
  <p>
    Hello! I'm Geramae Rotone, a Computer Science student with a strong interest in web development.
    I enjoy learning new technologies, improving my coding skills, and building simple yet meaningful projects.My goal is to continue developing my abilities and become 
‎a skilled and confident developer in the future.
  </p>
</section>

<!-- SKILLS SECTION WITH SHIELDS -->
<section id="skills" class="projects">
  <h2>Skills</h2>

  <div class="project">
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
  </div>
</section>

<section id="contact" class="contact">
  <h2>Contact Me</h2>
  <p>📧 <strong>Email:</strong> geramaerotone@gmail.com</p>

  <a href="mailto:geramaerotone@gmail.com">Email</a>
  <a href="https://github.com/yourusername" target="_blank">GitHub</a>
</section>

<footer>
  © 2026 Geramae Rotone
</footer>

</body>
</html>
