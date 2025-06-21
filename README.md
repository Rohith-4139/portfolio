# portfolio
A simple and responsive personal portfolio website built using HTML and CSS. This site showcases my projects, skills, and contact information in a clean and professional layout. Ideal for resumes, freelance profiles, or personal branding.
#code 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>B. Rohith Venkata Pavan Sai - Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
      color: #333;
    }

    header {
      background-color: #222;
      color: #fff;
      text-align: center;
      padding: 20px;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }

    section {
      padding: 20px;
      max-width: 900px;
      margin: auto;
      background-color: #fff;
      margin-top: 10px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }

    h1, h2 {
      color: #444;
    }

    ul {
      list-style: none;
      padding: 0;
    }

    li {
      margin-bottom: 10px;
    }

    .profile-pic {
      display: block;
      margin: 0 auto 20px;
      border-radius: 15px;
      max-width: 200px;
      height: auto;
      box-shadow: 0 0 8px rgba(0, 0, 0, 0.2);
    }

    footer {
      background-color: #222;
      color: #fff;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
    }

    a {
      color: #007BFF;
    }
  </style>
</head>
<body>

  <header>
    <h1>B. Rohith Venkata Pavan Sai</h1>
    <p>Student | CSE - AI & ML | Web & Python Developer</p>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#skills">Skills</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <img src="c:\Users\bomma\OneDrive\Pictures\pawan pic 4.jpg" alt="My Photo" class="profile-pic" />
    <p>
      I love building projects in Python, exploring AI, and creating web applications using HTML, CSS, and JavaScript.
      I’m a 3rd-year B.Tech CSE student specializing in AI & ML at SRMIST.
    </p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <ul>
      <li><strong>College Management System:</strong> Developed in Python with SQL database integration.</li>
      <li><strong>Responsive Portfolio Website:</strong> Built using HTML, CSS, and JavaScript.</li>
    </ul>
  </section>

  <section id="skills">
    <h2>My Skills</h2>
    <ul>
      <li><strong>1.</strong> Python Basics</li>
      <li><strong>2.</strong> HTML Basics</li>
      <li><strong>3.</strong> CSS Basics</li>
      <li><strong>4.</strong> JavaScript Basics</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <p>Email: <a href="mailto:rb8241@srmist.edu.in">rb8241@srmist.edu.in</a></p>
    <p>Phone: +91 9182805754</p>
    <p>GitHub: <a href="https://github.com/Rohith-4139/" target="_blank">github.com/Rohith-4139</a></p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/bomma-rohith-venkata-pavan-sai-6ab808296/" target="_blank">linkedin.com/in/bomma-rohith-venkata-pavan-sai</a></p>
  </section>

  <footer>
    <p>&copy; 2025 B. Rohith Venkata Pavan Sai</p>
  </footer>

</body>
</html>

