<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Geramae Rotone | Nature Portfolio</title>

  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">

  <style>
    /* General Reset */
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
      margin-bottom: 20px;
    }

    /* PROFILE PICTURE */
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
      box-shadow:
        0 0 25px #ff6ec7,
        0 0 50px #8a2be2,
        0 0 80px rgba(255,110,199,1);
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
      transition: 0.3s;
    }

    nav a:hover {
      color: #388e3c;
      text-shadow: 0 0 5px #66bb6a;
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
      text-shadow: 0 0 5px #66bb6a;
    }

    .about, .projects, .contact {
      margin-bottom: 50px;
      background: rgba(255,255,255,0.2);
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0 0 20px rgba(46,61,50,0.2);
      backdrop-filter: blur(5px);
    }

    .projects .project {
      background: rgba(76,175,80,0.1);
      padding: 20px;
      margin-bottom: 20px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(56,142,60,0.5);
    }

    .projects .project h3 {
      color: #388e3c;
    }

    .contact a {
      display: inline-block;
      margin: 10px;
      padding: 12px 25px;
      background: #4caf50;
      color: #fff;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
      transition: 0.3s;
    }

    .contact a:hover {
      background: #66bb6a;
      box-shadow: 0 0 15px #66bb6a, 0 0 30px #388e3c;
    }

    footer {
      text-align: center;
      padding: 20px;
      color: #4e4e4e;
      text-shadow: 0 0 3px #a5d6a7;
    }
  </style>
</head>

<body>

  <header>
    <h1>Geramae Rotone</h1>

    <!-- PROFILE IMAGE -->
  <img src="https://uploads.onecompiler.io/44a2gqpwf/44a2vzmbf/1000008761.jpg" class="profile-pic" alt="Profile Picture">

    Web Developer | Designer </p>
    "Confusion is part of programming"
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
      Hello! I'm Geramae Rotone Computer Science student with a strong interest in web development. I enjoy learning new technologies, improving my coding skills, and building simple 
‎yet meaningful projects. My goal is to continue developing my abilities and become 
‎a skilled and confident developer in the future.
    </p>
  </section>

  <section id="projects" class="projects">
  
   <!-- SKILLS -->
‎    <section>
‎        <h2>Skills</h2>
‎        <ul>
‎            <li>HTML5 & CSS</li>
‎            <li>Basic JavaScript</li>
‎           

  </section>

  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <p>Reach out through any platform below:</p>

    <p>📧 <strong>Email:</strong> geramaerotone@gmail.com</p>
    

    <a href="mailto:geramaerotone@gmail.com">Email</a>
    <a href="https://github.com/yourusername" target="_blank">GitHub</a>
