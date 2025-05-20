# PRODIGY_WD_04

##HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Ashraff Unnissa | Web Developer</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- Header / Home -->
  <header class="home-section">
    <img src="profile.jpg" alt="Ashraff Unnissa" class="profile-img">
    <h1>Hi, I'm <span class="highlight">Ashraff Unnissa</span></h1>
    <p>Web Developer • Creative Designer • C++ Enthusiast</p>
    <div class="skills-list">
      <span>HTML</span><span>CSS</span><span>JavaScript</span><span>React</span><span>C++</span><span>C</span><span>R</span>
    </div>
  </header>

  <!-- About Me -->
  <section class="about-section">
    <h2>About Me</h2>
    <p>
      I'm pursuing a B.Sc in Computer Science and Statistics at Christ (Deemed to be University), expected to graduate in 2027. I'm passionate about both programming and creativity — combining tech with art.
    </p>
    <p>
      I’ve worked on personal projects that reflect my skills in frontend development, object-oriented programming, and visual storytelling through code. I'm also deeply interested in painting, mandala art, and calligraphy.
    </p>
  </section>

  <!-- Projects -->
  <section class="projects-section">
    <h2>Projects</h2>
    <div class="projects-grid">
      <div class="project-card">
        <h3>Portfolio Website</h3>
        <p>A modern personal website built with HTML, CSS, and JavaScript.</p>
      </div>
      <div class="project-card">
        <h3>C++ Calculator</h3>
        <p>A console-based calculator using object-oriented programming in C++.</p>
      </div>
      <div class="project-card">
        <h3>Art Gallery</h3>
        <p>An online gallery showcasing my creative artwork using HTML and CSS.</p>
      </div>
      <div class="project-card">
        <h3>R Data Dashboard</h3>
        <p>Data visualizations and statistical insights built using R.</p>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 Ashraff Unnissa • Let's Connect!</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>


##CSS
/* General Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', sans-serif;
  line-height: 1.6;
  background: #f0f4f8;
  color: #333;
}

header, section {
  padding: 4rem 2rem;
  text-align: center;
}

.profile-img {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  border: 4px solid #00bfa5;
  box-shadow: 0 4px 8px rgba(0,0,0,0.2);
  margin-bottom: 1rem;
}

h1 {
  font-size: 2.5rem;
  margin-bottom: 0.5rem;
}

.highlight {
  color: #00bfa5;
}

.skills-list {
  margin-top: 1rem;
}

.skills-list span {
  background: #00bfa5;
  color: white;
  padding: 0.4rem 0.8rem;
  margin: 0.3rem;
  border-radius: 20px;
  display: inline-block;
  font-size: 0.9rem;
}

.about-section {
  background: white;
  max-width: 800px;
  margin: auto;
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
}

.projects-section {
  background: #e3f2fd;
}

.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 1.5rem;
  margin-top: 2rem;
  padding: 0 1rem;
}

.project-card {
  background: white;
  padding: 1.5rem;
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
  text-align: left;
}

.project-card h3 {
  margin-bottom: 0.5rem;
  color: #00796b;
}

footer {
  padding: 1rem;
  background: #00bfa5;
  color: white;
  text-align: center;
}


##Javascript
// Add any interactive functionality here (animations, toggles, etc.)
console.log("Portfolio site loaded!");
