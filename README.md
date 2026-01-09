<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Geramae Rotone | Nature Portfolio</title>

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">

  <!-- Font Awesome (Shield Icon) -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

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
    }

    header {
      text-align: center;
      padding: 80px 20px;
      background: rgba(255,255,255,0.5);
      border-radius: 15px;
      margin: 20px;
    }

    header h1 {
      font-size: 3rem;
      color: #388e3c;
    }

    .profile-pic {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      margin: 20px 0;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 20px;
    }

    nav a {
      text-decoration: none;
      font-weight: bold;
      color: #2e3d32;
    }

    section {
      max-width: 900px;
      margin: 40px auto;
      padding: 30px;
      background: rgba(255,255,255,0.2);
      border-radius: 15px;
    }

    h2 {
      text-align: center;
      margin-bottom: 20px;
      color: #2e7d32;
    }

    /* 🔰 SKILLS ICON CSS */
    .skills-list {
      list-style: none;
      padding-left: 0;
    }

    .skills-list li {
      font-size: 1.1rem;
      margin: 12px 0;
      display: flex;
      align-items: center;
      gap: 12px;
    }

    .skills-list i {
      color: #388e3c;
      text-shadow: 0 0 6px #66bb6a;
    }
  </style>
</head>

<body>

<header>
  <h1>Geramae Rotone</h1>
  <img src="https://uploads.onecompiler.io/44a2gqpwf/44a2vzmbf/1000008761.jpg" class="profile-pic">
  <p>Web Developer | Designer</p>
  <p>"Confusion is part of programming"</p>
</header>

<nav>
  <a href="#about">About</a>
  <a href="#skills">Skills</a>
  <a href="#contact">Contact</a>
</nav>

<section id="about">
  <h2>About Me</h2>
  <p>
    Hello! I'm Geramae Rotone, a Computer Science student with a strong interest in web development.
  </p>
</section>

<!-- ✅ SKILLS WITH SHIELD ICON -->
<section id="skills">
  <h2>Skills</h2>
  <ul class="skills-list">
    <li><i class="fa-solid fa-shield"></i> HTML5 & CSS</li>
    <li><i class="fa-solid fa-shield"></i> Basic JavaScript</li>
  </ul>
</section>

<section id="contact">
  <h2>Contact</h2>
  <p>📧 geramaerotone@gmail.com</p>
</section>

</body>
</html>
