<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: "Poppins", sans-serif;
      line-height: 1.6;
      background: #f4f4f4;
      color: #333;
    }
    header {
      background: linear-gradient(to right, #6dd5ed, #2193b0);
      color: white;
      text-align: center;
      padding: 60px 20px;
    }
    header img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      margin-bottom: 15px;
      border: 4px solid white;
    }
    header h1 { font-size: 2.5rem; }
    header p { font-size: 1.2rem; }

    nav {
      background: #2193b0;
      display: flex;
      justify-content: center;
      padding: 10px;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
      transition: 0.3s;
    }
    nav a:hover { color: #ffeb3b; }

    section {
      padding: 60px 20px;
      max-width: 900px;
      margin: auto;
    }
    section h2 {
      text-align: center;
      margin-bottom: 30px;
      font-size: 2rem;
      color: #2193b0;
    }
    .projects, .skills {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .card {
      background: white;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      transition: 0.3s;
    }
    .card:hover { transform: translateY(-5px); }
    .card h3 { margin-bottom: 10px; color: #2193b0; }

    form {
      display: flex;
      flex-direction: column;
      gap: 15px;
    }
    form input, form textarea {
      padding: 12px;
      border: 1px solid #ccc;
      border-radius: 8px;
      font-size: 1rem;
    }
    form button {
      background: #2193b0;
      color: white;
      border: none;
      padding: 12px;
      border-radius: 8px;
      font-size: 1rem;
      cursor: pointer;
      transition: 0.3s;
    }
    form button:hover { background: #176d82; }

    footer {
      text-align: center;
      padding: 20px;
      background: #2193b0;
      color: white;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    <img src="assets/me.jpg" alt="My Photo">
    <h1>Hi, I'm Jitesh</h1>
    <p>Web Developer | Programmer | Learner</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#skills">Skills</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Me</h2>
    <p>
      I am a passionate developer who loves creating modern websites and applications. 
      Always eager to learn new technologies and improve my skills.
    </p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="projects">
      <div class="card">
        <h3>Project 1</h3>
        <p>A simple website built with HTML, CSS, and JavaScript.</p>
      </div>
      <div class="card">
        <h3>Project 2</h3>
        <p>A portfolio site hosted on GitHub Pages.</p>
      </div>
      <div class="card">
        <h3>Project 3</h3>
        <p>A responsive landing page with modern design.</p>
      </div>
    </div>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <div class="skills">
      <div class="card"><h3>HTML & CSS</h3></div>
      <div class="card"><h3>JavaScript</h3></div>
      <div class="card"><h3>React (Learning)</h3></div>
      <div class="card"><h3>Git & GitHub</h3></div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <form>
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea rows="5" placeholder="Your Message"></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>© 2025 Jitesh | Made with ❤️ on GitHub Pages</p>
  </footer>

</body>
</html>
