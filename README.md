<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Hello there! I'm (b1cey)</title>
  <style>
    /* Basic Reset & Styling */
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      margin: 0;
      padding: 0;
      color: #333;
    }
    .container {
      max-width: 800px;
      margin: 40px auto;
      padding: 20px;
      background: #fff;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      border-radius: 8px;
    }
    /* Animation Styles */
    .animated-title {
      text-align: center;
      animation: fadeIn 2s ease-in-out;
    }
    .animated-subtitle {
      text-align: center;
      animation: slideIn 2s ease-in-out;
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    @keyframes slideIn {
      from { transform: translateY(-20px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }
    /* Badge Styling */
    .badges {
      text-align: center;
      margin-top: 20px;
    }
    .badges img {
      margin: 0 5px;
    }
    /* Section Styling */
    .section {
      margin-top: 40px;
    }
    .section h2 {
      border-bottom: 2px solid #ddd;
      padding-bottom: 10px;
    }
    hr {
      margin: 40px 0;
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- Centered Title & Subtitle with Animations -->
    <h1 class="animated-title">Hello there! 👋 I'm (b1cey)</h1>
    <h3 class="animated-subtitle">A Final-Year Computer Science Undergraduate</h3>
    
    <!-- Profile Views Badge -->
    <p align="center">
      <img src="https://komarev.com/ghpvc/?username=b1cey&label=Profile%20views&color=0e75b6&style=flat" alt="Profile Views" />
    </p>
    
    <!-- Custom Badges -->
    <p class="badges">
      <img src="https://img.shields.io/badge/Status-Final%20Year%20Undergrad-blue?style=flat-square" alt="Status Badge" />
      <img src="https://img.shields.io/badge/Focus-Software%20Development-brightgreen?style=flat-square" alt="Focus Badge" />
      <img src="https://img.shields.io/badge/Next%20Stop-MSc%20in%20Software%20Engineering-orange?style=flat-square" alt="Next Stop Badge" />
      <img src="https://img.shields.io/badge/Tools-React%2C%20Tailwind%2C%20Vite%2C%20Next.js%2C%20HTML%2C%20CSS-blueviolet?style=flat-square" alt="Tech Stack Badge" />
    </p>
    
    <hr>
    
    <!-- About Me Section -->
    <div class="section">
      <h2>🏫 About Me</h2>
      <p>I'm <strong>b1cey</strong>, and I'm a final-year undergraduate student pursuing <strong>Computer Science</strong>. My academic journey has been driven by a passion for technology and innovation, and I've gained extensive experience in:</p>
      <ul>
        <li><strong>Software Development</strong></li>
        <li><strong>Web Design</strong></li>
      </ul>
      <p>After graduation, I'm planning to pursue an <strong>MSc in Software Engineering</strong> to deepen my expertise and explore advanced topics in <strong>software architecture</strong>, <strong>machine learning</strong>, and <strong>artificial intelligence</strong>.</p>
    </div>
    
    <!-- Tech Stack Section -->
    <div class="section">
      <h2>⚡ Tech Stack</h2>
      <ul>
        <li><strong>Frontend:</strong> React, Tailwind CSS, HTML, CSS, Vite</li>
        <li><strong>Learning:</strong> Next.js</li>
        <li><strong>Other Skills:</strong> (Mention any other frameworks, tools, or languages you’re comfortable with)</li>
      </ul>
    </div>
    
    <!-- Future Goals Section -->
    <div class="section">
      <h2>🔭 Future Goals</h2>
      <ul>
        <li><strong>Master’s in Software Engineering</strong>: Eager to delve deeper into advanced software development, machine learning, and AI.</li>
        <li><strong>Open Source Contributions</strong>: Looking to collaborate on open-source projects that align with my interests.</li>
      </ul>
    </div>
    
    <p align="center">
      <em>Thanks for stopping by! Feel free to explore my repositories or reach out if you'd like to collaborate.</em>
    </p>
  </div>
</body>
</html>
