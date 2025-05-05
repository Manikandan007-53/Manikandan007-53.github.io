
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>CyberDev Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Share+Tech+Mono&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Share Tech Mono', monospace;
      background-color: #0d1117;
      color: #00ff9c;
      overflow-x: hidden;
    }header {
  padding: 60px 20px;
  text-align: center;
  background: #0a0f13;
  border-bottom: 2px solid #00ff9c;
}

h1 {
  font-size: 2.8em;
  margin-bottom: 10px;
}

.terminal-text {
  font-size: 1.2em;
  white-space: nowrap;
  overflow: hidden;
  border-right: 2px solid #00ff9c;
  width: 0;
  animation: typing 3s steps(40, end) forwards, blink 0.8s infinite;
}

@keyframes typing {
  to {
    width: 100%;
  }
}

@keyframes blink {
  50% {
    border-color: transparent;
  }
}

section {
  padding: 40px 20px;
  border-bottom: 1px dashed #00ff9c;
}

h2 {
  color: #00d0ff;
  font-size: 1.8em;
  margin-bottom: 20px;
}

.projects, .certificates {
  display: grid;
  gap: 20px;
}

.item {
  background-color: #121d26;
  padding: 20px;
  border: 1px solid #00ff9c;
  border-radius: 10px;
}

.item h3 {
  margin: 0 0 10px;
  color: #00f7ff;
}

.item a {
  color: #00ff9c;
  text-decoration: none;
}

footer {
  text-align: center;
  padding: 30px 10px;
  color: #888;
}

  </style>
</head>
<body>
  <header>
    <h1>Hi, I'm [Your Name]</h1>
    <div class="terminal-text">Web Developer & Cyber Security Enthusiast</div>
  </header>  <section>
    <h2>About Me</h2>
    <p>I'm a passionate web developer and cyber security enthusiast. I love crafting secure, responsive web apps and exploring system vulnerabilities to enhance digital safety.</p>
  </section>  <section>
    <h2>Projects</h2>
    <div class="projects">
      <div class="item">
        <h3>Secure Login System</h3>
        <p>A secure user authentication system with hashed passwords and token-based sessions.</p>
        <a href="#">View on GitHub</a>
      </div>
      <div class="item">
        <h3>Vulnerability Scanner</h3>
        <p>Python tool to detect vulnerabilities in installed applications and OS configuration.</p>
        <a href="#">View on GitHub</a>
      </div>
    </div>
  </section>  <section>
    <h2>Certificates</h2>
    <div class="certificates">
      <div class="item">
        <h3>CEH v11</h3>
        <p>Certified Ethical Hacker from EC-Council</p>
      </div>
      <div class="item">
        <h3>Responsive Web Design</h3>
        <p>Certificate from freeCodeCamp covering HTML, CSS, and JavaScript</p>
      </div>
    </div>
  </section>  <section>
    <h2>Skills</h2>
    <p>HTML5, CSS3, JavaScript, React, Python, Flask, Nmap, Burp Suite, Kali Linux, Git, Linux Shell</p>
  </section>  <section>
    <h2>Contact</h2>
    <p>Email: your.email@example.com</p>
    <p>GitHub: github.com/yourusername</p>
    <p>LinkedIn: linkedin.com/in/yourprofile</p>
  </section>  <footer>
    <p>&copy; 2025 [Your Name]. All rights reserved.</p>
  </footer>
</body>
</html>
```
