<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>HTML & CSS CODING | PRECIOUS</title>
    <link rel="stylesheet" href="style.css">
    <script src="script.js" defer></script>
  </head>
  
  <header class="navbar">
    <h1 class="logo">PIXEL</h1>
    <ul>
      <li><a href="#about">About</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#project">Projects</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
    <button id="theme-toggle" class="theme-btn">🌙</button>
  </header>
  
  <body>
    
    <section class="about" id="about">
      <h2>About Me</h2>
      <p>Hi, I'm <strong>PRECIOUS!</strong> I'm a passionate <strong>Full-stack Developer</strong> based in <strong>Nigeria</strong>.</p>
      <p>I love turning complex problem into simple, beautiful and intuitive designs.<br>When I'm not coding, you can find me <strong>hiking, playing chess or reading.</strong></p>
    </section>
    
    <section class="skills" id="skills">
      <h2>My Tech Stack</h2>
      <div class="skills-container">
        <div class="skill-card">HTML5</div>
        <div class="skill-card">CSS3</div>
        <div class="skill-card">JavaScript</div>
        
        <div class="skill-card">Kotlin</div>
        <div class="skill-card">Java</div>
        <div class="skill-card">Python</div>
        <div class="skill-card">TypeScript</div>
      </div>
    </section>
    
    <section class="project" id="project">
      <h2>Featured Projects</h2>
      <div class="project-grid">
        
        <div class="project-card">
          <h3>Android Task Manager</h3>
          <p>A native mobile application built with <strong>Kotlin</strong> to help users organize daily goals.</p>
          <div class="tech-used">Kotlin • Firebase</div>
        </div>
        
        <div class="project-card">
          <h3>E-Commerce Interface</h3>
          <p>A responsive web front-end focusing on clean UI and fast loading speeds.</p>
          <div class="tech-used">HTML • CSS • JavaScript</div>
        </div>
        
        <div class="project-card">
          <h3>Data Scraper</h3>
          <p>A Python-based tool that extracts and organize real-time market data.</p>
          <div class="tech-used">Python • BeautifulSoup</div>
          
        </div>
    </section>
    
    <section class="contact" id="contact">
      <h2>Get in Touch</h2>
      <div class="contact-container">
        <div class="contact-info">
          <p>I'm always open to discussing new projects or creative ideas.</p>
          <p><strong>Email:</strong> <a href="mailto:blockwise00@gmail.com"><i>blockwise00@gmail.com</i></a></p>
          <p><strong>Location:</strong> Gwagwalada Abuja, Nigeria.</p>
        </div>
        
        <form class="contact-form">
          <input type="text" placeholder="Your Name" required>
          <input type="email" placeholder="Your Email" required>
          <textarea placeholder="Your Message" rows="5"></textarea>
          <button type="submit" class="submit-btn">Send Message</button>
        </form>
        
      </div>
      
    </section>
    
    <footer>
    <div class="footer-content">
      <p>&COPY; 2026 PIXEL. All right reserved.</p>
      <div class="social-links">
        <a href="https://github.com/blockwise00" target="_blank">GitHub</a>
        <a href="https://linkedin.com/in/blockwise00" target="_blank">LinkedIn</a>
      </div>
    </div>
  </footer>
  
  <a href="#about" class="back-to-top">↑</a>
  
  </body>
</html>
