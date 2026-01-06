<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Nzaoo | Full-Stack Dev</title>
  <link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'JetBrains Mono', monospace;
    }
    body {
      background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
      color: #fff;
      overflow-x: hidden;
    }
    header {
      text-align: center;
      padding: 3rem 1rem 1rem;
      animation: fadeIn 1.2s ease-out;
    }
    h1 {
      font-size: 3rem;
      color: #00d9ff;
    }
    p.subtitle {
      font-size: 1.2rem;
      margin-top: 0.5rem;
      color: #ccc;
    }
    section {
      padding: 2rem 1rem;
      max-width: 900px;
      margin: 0 auto;
      animation: fadeInUp 1s ease-out both;
    }
    section:nth-child(even) {
      background: rgba(255, 255, 255, 0.05);
      border-radius: 10px;
      margin-bottom: 2rem;
    }
    h2 {
      color: #f85d7f;
      margin-bottom: 1rem;
    }
    ul {
      list-style-type: square;
      padding-left: 1.5rem;
    }
    a {
      color: #4ecdc4;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    .projects .card {
      background: #112;
      margin-bottom: 1.5rem;
      border: 1px solid #333;
      padding: 1rem;
      border-radius: 8px;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .projects .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 5px 15px rgba(0, 217, 255, 0.2);
    }
    footer {
      text-align: center;
      padding: 2rem 1rem;
      font-size: 0.9rem;
      color: #aaa;
    }
    .typing {
      display: inline-block;
      overflow: hidden;
      white-space: nowrap;
      animation: typing 3s steps(30, end), blink 0.75s step-end infinite;
      border-right: 3px solid #00d9ff;
      font-size: 1.3rem;
    }
    @keyframes fadeIn {
      from {opacity: 0; transform: translateY(-20px);}
      to {opacity: 1; transform: translateY(0);}
    }
    @keyframes fadeInUp {
      from {opacity: 0; transform: translateY(40px);}
      to {opacity: 1; transform: translateY(0);}
    }
    @keyframes typing {
      from { width: 0 }
      to { width: 100% }
    }
    @keyframes blink {
      50% { border-color: transparent }
    }
  </style>
</head>
<body>
  <header>
    <h1>Hi, I'm Nzaoo 👋</h1>
    <p class="typing">Full-Stack Developer | UI/UX Lover | Clean Code Enthusiast</p>
  </header>

  <section>
    <h2>🔎 Quick Summary</h2>
    <ul>
      <li>Based in Vietnam 🌏</li>
      <li>Specializing in React, Next.js, Node.js</li>
      <li>Passionate about frontend architecture and UX</li>
      <li>Always learning something new</li>
    </ul>
  </section>

  <section class="projects">
    <h2>🚀 Featured Projects</h2>
    <div class="card">
      <h3>NZaoCard – Digital Card Generator</h3>
      <p>Create, share, and style personal cards in seconds using Next.js + Firebase.</p>
      <a href="https://linkcard-psi.vercel.app/">Live Demo</a> | <a href="https://github.com/nzaoo/linkcard_generator">Repo</a>
    </div>
    <div class="card">
      <h3>Interactive Business Card</h3>
      <p>Animated, responsive card using pure HTML/CSS/JS with audio interactions.</p>
      <a href="https://nzaoo.github.io/nzao_card/">Live Demo</a> | <a href="https://github.com/nzaoo/nzao_card">Repo</a>
    </div>
    <div class="card">
      <h3>3D Maze Game</h3>
      <p>First-person maze game with collectibles built using Three.js.</p>
      <a href="https://nzaoo.github.io/mini_game_maze_3d/">Play Game</a> | <a href="https://github.com/nzaoo/mini_game_maze_3d">Repo</a>
    </div>
  </section>

  <section>
    <h2>📬 Contact</h2>
    <p>Email: <a href="mailto:nzaoo.1372@gmail.com">nzaoo.1372@gmail.com</a></p>
    <p>LinkedIn: <a href="https://linkedin.com/in/nzaoo">@nzaoo</a></p>
    <p>Portfolio: <a href="https://nzaoo.github.io">nzaoo.github.io</a></p>
  </section>

  <footer>
    <p>“Clean code always looks like it was written by someone who cares.” – Robert C. Martin</p>
  </footer>
</body>
</html>
