<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <style>
    /* Reset */
    * { margin: 0; padding: 0; box-sizing: border-box; }

    body {
      font-family: 'Segoe UI', sans-serif;
      background: #fdfdfd;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(135deg, #ff416c, #ff4b2b);
      color: white;
      text-align: center;
      padding: 3rem 1rem;
    }
    header h1 { font-size: 2.5rem; }
    header p { font-size: 1.2rem; margin-top: 0.5rem; }

    nav {
      background: #222;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 1rem;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-size: 1rem;
      padding: 0.5rem 1rem;
      border-radius: 20px;
      transition: background 0.3s;
    }
    nav a:hover { background: #ff416c; }

    section {
      padding: 2.5rem 1rem;
      max-width: 900px;
      margin: auto;
    }
    h2 {
      margin-bottom: 1rem;
      font-size: 1.8rem;
      color: #ff416c;
    }

    .about {
      text-align: center;
      font-size: 1.1rem;
    }

    .projects {
      display: grid;
      gap: 1.5rem;
    }
    .card {
      background: white;
      padding: 1.5rem;
      border-radius: 12px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      transition: transform 0.2s, box-shadow 0.2s;
    }
    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 15px rgba(0,0,0,0.15);
    }
    .card h3 { margin-bottom: 0.5rem; color: #222; }
    .card p { font-size: 0.95rem; }

    .btn {
      display: inline-block;
      margin-top: 0.8rem;
      background: #ff416c;
      color: white;
      padding: 0.5rem 1rem;
      border-radius: 6px;
      text-decoration: none;
      transition: background 0.3s;
    }
    .btn:hover { background: #ff4b2b; }

    .contact {
      text-align: center;
      font-size: 1.1rem;
    }
    .contact a {
      color: #ff416c;
      text-decoration: none;
      font-weight: bold;
    }

    footer {
      background: #222;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
      font-size: 0.9rem;
    }

    /* Responsive */
    @media (max-width: 600px) {
      header h1 { font-size: 2rem; }
      nav { flex-wrap: wrap; gap: 10px; }
    }
  </style>
</head>
<body>

  <header>
    <h1>Hi, I'm sri Harshini</h1>
    <p>Web Developer | Designer | Learner</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about" class="about">
    <h2>About Me</h2>
    <p>Hello! I’m a student who loves building websites and learning new skills.  
       My goal is to create clean, modern, and user-friendly designs.</p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="projects">
      <div class="card">
        <h3>Portfolio Website</h3>
        <p>A responsive website to showcase my work and skills.</p>
        <a href="#" class="btn">View Project</a>
      </div>
      <div class="card">
        <h3>Calculator App</h3>
        <p>A simple calculator made with HTML, CSS, and JavaScript.</p>
        <a href="#" class="btn">View Project</a>
      </div>
      <div class="card">
        <h3>To-Do List</h3>
        <p>A task manager app to keep track of daily goals.</p>
        <a href="#" class="btn">View Project</a>
      </div>
    </div>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <p>Email: <a href="mailto: sriharshini189@gmail.com">SriHarshini189@gmail.com</a></p>
    <p>LinkedIn: <a href="#">linkedin.com/in/yourprofile</a></p>
    <p>GitHub: <a href="#">github.com/sri-harshini77</a></p>
  </section>

  <footer>
    <p>© 2025 [sri Harshini] | Built with ❤️</p>
  </footer>

</body>
</html>
