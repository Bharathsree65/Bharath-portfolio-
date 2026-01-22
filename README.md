<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bharath | Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Hi, I'm Bharath 👋</h1>
    <p>Student</p>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>Hi, I'm Bharath — a web developer passionate about building clean, functional websites. I specialize in HTML, CSS, and Django, and I enjoy turning ideas into practical digital solutions. Explore my projects below and feel free to connect!.</p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>Inventory Management System</h3>
      <p>A Django-based system with diagrams, requirements, and polished documentation.</p>
      <a href="#">View Project</a>
    </div>
  </section>
    <section id="projects">
  <h2>Projects</h2>
  <div class="project">
    <h3>Full Stack Development Internship Project</h3>
    <p>
      Built a full-stack web application using Django and CSS. 
      Features include user authentication, CRUD operations, and a responsive design.
    </p>
    <ul>
      <li>Frontend: HTML, CSS</li>
      <li>Backend: JavaScript</li>
      <li>Database: Firebase</li>
    </ul>
    <a href="https://github.com/yourusername/project" target="_blank">View on GitHub</a>
  </div>
</section>
<section id="skills">
  <h2>Technical Skills</h2>
  <ul class="skills-list">
    <li>HTML5</li>
    <li>CSS3</li>
    <li>JavaScript</li>
    <li>Python</li>
    <li>UI/ UX Design</li>
    <li>Java</li>
    <li>Responsive Web Design</li>
  </ul>
</section>
<section id="soft-skills">
  <h2>Non-Technical Skills</h2>
  <ul class="soft-skills-list">
    <li>Effective Communication</li>
    <li>Team Collaboration</li>
    <li>Problem-Solving</li>
    <li>Time Management</li>
    <li>Adaptability</li>
  </ul>
</section>
  <section id="contact">
    <h2>Contact</h2>
    <p>Email: bharathtamil5555@gmail.com</p>
  </section>
</body>
</html>
/* Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Global styles */
body {
  font-family: 'Times New Roman', Times, serif;
  line-height: 1.7;
  background-color: #ffffff;
  color: #222;
}

/* Header */
header {
  background: #1a1a1a;
  color: #f5f5f5;
  text-align: center;
  padding: 80px 20px;
}

header h1 {
  font-size: 2.8rem;
  font-weight: 600;
  margin-bottom: 10px;
}

header p {
  font-size: 1.2rem;
  color: #cccccc;
  max-width: 700px;
  margin: auto;
}

/* Section styling */
section {
  padding: 60px 20px;
  max-width: 1000px;
  margin: auto;
}

section h2 {
  font-size: 2rem;
  margin-bottom: 25px;
  color: #1a1a1a;
  border-bottom: 2px solid #007acc;
  display: inline-block;
  font-weight: 500;
}

/* Project cards */
.project {
  background: #fafafa;
  border: 1px solid #e0e0e0;
  border-radius: 6px;
  padding: 25px;
  margin-bottom: 25px;
  transition: box-shadow 0.3s ease;
}

.project:hover {
  box-shadow: 0 6px 16px rgba(0,0,0,0.08);
}

.project h3 {
  margin-bottom: 12px;
  color: #1a1a1a;
  font-weight: 600;
}

.project a {
  text-decoration: none;
  color: #007acc;
  font-weight: 500;
}

.project a:hover {
  color: #005f99;
}

/* Skills section */
#skills {
  background: #f9f9f9;
  padding: 50px 20px;
  text-align: center;
}

.skills-list {
  list-style: none;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 12px;
}

.skills-list li {
  background: #007acc;
  color: white;
  padding: 10px 18px;
  border-radius: 4px;
  font-weight: 500;
  transition: background 0.3s ease;
}

.skills-list li:hover {
  background: #005f99;
}

/* Soft skills section */
#soft-skills {
  background: #ffffff;
  padding: 50px 20px;
  text-align: center;
}

.soft-skills-list {
  list-style: none;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 12px;
}

.soft-skills-list li {
  background: #444;
  color: #f5f5f5;
  padding: 10px 18px;
  border-radius: 4px;
  font-weight: 500;
  transition: background 0.3s ease;
}

.soft-skills-list li:hover {
  background: #222;
}

/* Contact section */
#contact {
  text-align: center;
  padding: 40px 20px;
}

#contact p {
  margin: 8px 0;
}

#contact a {
  color: #007acc;
  text-decoration: none;
  font-weight: 500;
}

#contact a:hover {
  color: #005f99;
}

/* Responsive */
@media (max-width: 600px) {
  header h1 {
    font-size: 2rem;
  }
  section h2 {
    font-size: 1.4rem;
  }
}
