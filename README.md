<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="styles.css">
  <title>Rakshana - Portfolio</title>
</head>
<style>
  body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    background-color: #0b1400;
    color: #fff;
    transition: background-color 0.3s ease, color 0.3s ease;
  }

  body::before {
    font-size: 8rem;
    font-weight: 100;
    font-style: normal;
  }
  .container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
  }
  
  header, nav, section, footer {
    padding: 50px 0;
  }
  
  header {
    text-align: center;
  }
  
  header img {
    border-radius: 100%;
    max-width: 150px;
    margin-top: 20px;
  }
  
  nav ul {
    list-style: none;
    display: flex;
    justify-content: space-between;
  }
  
  nav a, button {
    text-decoration: none;
    color: #fff;
    font-weight: bold;
    font-size: 16px;
    transition: color 0.3s ease;
  }
  
  nav a:hover, button:hover {
    color: #8cff00;
  }
  
  .section {
    background-color: #000000;
    padding: 30px 0;
  }
  
  h2 {
    color: #5eff00;
  }
  
  ul {
    list-style: none;
    padding: 0;
  }
  
  ul li {
    margin-bottom: 10px;
  }
  
  a {
    text-decoration: none;
    color: #3498db;
  }
  
  a:hover {
    color: #2980b9;
  }
  
  footer {
    background-color: #222;
    text-align: center;
    color: #777;
    padding: 20px 0;
    position: fixed;
    bottom: 0;
    width: 100%;
  }
  </style>
<body>
  <header>
    <div class="container">
    <img src=![rakshana](C:\Users\shiva\Pictures\raksh.jpeg) alt="Your Image"> 
      <h1>Rakshana</h1>
      <p>Tech enthusiast | Front-End development</p>
      
    </div>
  </header>

  <nav>
    <div class="container">
      <ul>
    
        <li><a href="#skills">Skills</a></li>
        <li><a href="#linkedin">LinkedIn</a></li>
        <li><a href="#github">GitHub</a></li>
      </ul>
    </div>
  </nav>

  <section id="about" class="section">
    <div class="container">
      <h2>About Me</h2>
      <p>Welcome to my digital space! I'm Rakshana a sophomore pursuing bachelors degree in Information Technology at SRM University. Alongside my studies, I've engaged in virtual internships, enhancing my practical skills in web development.

        As a Front-End developer I specialize in creating compelling user interfaces using HTML, CSS, and various JavaScript frameworks. My passion extends to image processing  and python programming, where I consistently push the boundaries of what's possible.
        
        I approach my work with a blend of creativity and passion, always seeking opportunities to learn and innovate. Excited about the dynamic field of web design, I am actively exploring new facets and staying aware of emerging trends. Let's collaborate to turn your ideas into reality! Explore my portfolio, and feel free to reach out for exciting projects or collaborations. </p>
    </div>
  </section>

  <section id="skills" class="section">
    <div class="container">
      <h2>Skills</h2>
      <ul>
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
        <li>python</li>
        <li>image processing</li>
        <!-- Add more skills as needed -->
      </ul>
    </div>
  </section>

  <section id="linkedin" class="section">
    <div class="container">
      <h2>LinkedIn</h2>
      <a href="https://www.linkedin.com/in/rakshanas-22r/" target="_blank" rel="noopener noreferrer">Visit LinkedIn Profile</a>
    </div>
  </section>

  <section id="github" class="section">
    <div class="container">
      <h2>GitHub</h2>
      <a href="https://github.com/Rakshana2204" target="_blank" rel="noopener noreferrer">Visit GitHub Profile</a>
    </div>
  </section>


  <script>document.getElementById('themeToggle').addEventListener('click', function() {
    document.body.classList.toggle('light-theme');
  });
  </script>

  <script src="script.js"></script>
</body>
</html>
