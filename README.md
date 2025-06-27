/* Global Styles */
body {
  margin: 0;
  font-family: 'Inter', sans-serif;
  background: #f9f9f9;
  color: #333;
}

.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background: #111;
  padding: 1rem 2rem;
  color: #fff;
}

.navbar a {
  color: #ddd;
  text-decoration: none;
  margin-left: 1rem;
  transition: color 0.3s ease;
}

.navbar a:hover {
  color: #00ffc8;
}

.hero {
  padding: 5rem 2rem;
  text-align: center;
  background: linear-gradient(145deg, #000, #222);
  color: #fff;
}

.btn {
  display: inline-block;
  margin-top: 1rem;
  padding: 0.75rem 1.5rem;
  background: #00ffc8;
  color: #111;
  font-weight: bold;
  border: none;
  border-radius: 5px;
  text-decoration: none;
  transition: background 0.3s ease;
}

.btn:hover {
  background: #00dab2;
}

.highlights {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 2rem;
  padding: 3rem 2rem;
  background: #fff;
}

.highlight-box {
  background: #f0f0f0;
  padding: 2rem;
  border-radius: 10px;
  max-width: 300px;
  text-align: center;
  box-shadow: 0 10px 20px rgba(0,0,0,0.1);
}

footer.footer {
  text-align: center;
  padding: 2rem;
  background: #111;
  color: #aaa;
  font-size: 0.9rem;
}

main.about, main.projects, main.contact {
  padding: 4rem 2rem;
  max-width: 800px;
  margin: auto;
}

.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 2rem;
  margin-top: 2rem;
}

.project-card {
  background: #fff;
  border: 1px solid #eee;
  padding: 1.5rem;
  border-radius: 10px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.05);
  transition: transform 0.3s ease;
}

.project-card:hover {
  transform: translateY(-5px);
}

form {
  display: flex;
  flex-direction: column;
  gap: 1rem;
  margin-top: 2rem;
}

input, textarea, button {
  padding: 0.75rem;
  border-radius: 5px;
  border: 1px solid #ccc;
  font-family: inherit;
}

button {
  background: #00ffc8;
  color: #111;
  font-weight: bold;
  cursor: pointer;
}

button:hover {
  background: #00dab2;
}

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Projects | Kunal Kaul</title>
  <link rel="stylesheet" href="/styles/main.css" />
</head>
<body>
  <header class="navbar">
    <div class="logo">Kunal Kaul</div>
    <nav>
      <a href="/index.html">Home</a>
      <a href="/about.html">About</a>
      <a href="/projects.html">Projects</a>
      <a href="/contact.html">Contact</a>
    </nav>
  </header>

  <main class="projects">
    <h1>Featured Projects</h1>
    <div class="project-grid">
      <div class="project-card">
        <h2>Creator Branding Kit</h2>
        <p>Built a complete brand kit including logo, color palette, and Instagram templates for a digital creator.</p>
      </div>
      <div class="project-card">
        <h2>UI Concept for News App</h2>
        <p>Designed a mobile UI for a modern news aggregator app, focusing on clarity and speed of use.</p>
      </div>
      <div class="project-card">
        <h2>AI + Visual Content Campaign</h2>
        <p>Combined MidJourney and ChatGPT outputs into engaging visuals and captions for a viral ad campaign.</p>
      </div>
    </div>
  </main>

  <footer class="footer">
    <p>&copy; 2025 Kunal Kaul. All rights reserved.</p>
  </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact | Kunal Kaul</title>
  <link rel="stylesheet" href="/styles/main.css" />
</head>
<body>
  <header class="navbar">
    <div class="logo">Kunal Kaul</div>
    <nav>
      <a href="/index.html">Home</a>
      <a href="/about.html">About</a>
      <a href="/projects.html">Projects</a>
      <a href="/contact.html">Contact</a>
    </nav>
  </header>

  <main class="contact">
    <h1>Let's Connect</h1>
    <p>Got a project, collaboration idea, or just want to say hi? Drop me a message!</p>
    <form action="mailto:kunalkaul09@gmail.com" method="post" enctype="text/plain">
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required>

      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>

      <label for="message">Message:</label>
      <textarea id="message" name="message" rows="5" required></textarea>

      <button type="submit">Send Message</button>
    </form>
  </main>

  <footer class="footer">
    <p>&copy; 2025 Kunal Kaul. All rights reserved.</p>
  </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>About | Kunal Kaul</title>
  <link rel="stylesheet" href="/styles/main.css" />
</head>
<body>
  <header class="navbar">
    <div class="logo">Kunal Kaul</div>
    <nav>
      <a href="/index.html">Home</a>
      <a href="/about.html">About</a>
      <a href="/projects.html">Projects</a>
      <a href="/contact.html">Contact</a>
    </nav>
  </header>

  <main class="about">
    <h1>About Me</h1>
    <p>Hey, I'm Kunal — a passionate designer who blends creativity, modern UI/UX practices, and AI technologies to deliver standout digital experiences. With over 3 years of freelance and agency work, I’ve helped creators, news outlets, and small brands shape their digital identity through visually striking and high-performing design.</p>
    <h2>My Superpowers</h2>
    <ul>
      <li>Graphic Design (Posters, Reels, Thumbnails)</li>
      <li>UI/UX Design (Mobile + Web Apps)</li>
      <li>Trend Research & Content Strategy</li>
      <li>AI Tools: Midjourney, ChatGPT, DALL·E</li>
      <li>Adobe Suite, Canva, Figma</li>
    </ul>
  </main>

  <footer class="footer">
    <p>&copy; 2025 Kunal Kaul. All rights reserved.</p>
  </footer>
</body>
</html>
