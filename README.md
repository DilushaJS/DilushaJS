<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dilusha Jayanindu Shashipriya - Full-Stack Developer</title>
  <style>
    :root {
      --primary-color: #0e76a8;
      --secondary-color: #112240;
      --accent-color: #64ffda;
      --text-primary: #ccd6f6;
      --text-secondary: #8892b0;
      --bg-color: #0a192f;
      --card-bg: rgba(17, 34, 64, 0.7);
    }
    
    body {
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
      line-height: 1.6;
      color: var(--text-primary);
      background-color: var(--bg-color);
      margin: 0;
      padding: 0;
    }
    
    .container {
      max-width: 1000px;
      margin: 0 auto;
      padding: 40px 20px;
    }
    
    .header {
      text-align: center;
      margin-bottom: 40px;
      position: relative;
    }
    
    h1 {
      font-size: 3.5rem;
      margin: 10px 0;
      background: linear-gradient(90deg, #64ffda, #0e76a8);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      position: relative;
    }
    
    h3 {
      color: var(--text-secondary);
      font-size: 1.5rem;
      font-weight: 400;
      margin-top: 0;
    }
    
    .profile-views {
      display: inline-block;
      background-color: rgba(14, 117, 182, 0.2);
      padding: 8px 15px;
      border-radius: 20px;
      margin: 15px auto;
      border: 1px solid rgba(14, 117, 182, 0.4);
    }
    
    .section-title {
      font-size: 1.8rem;
      position: relative;
      padding-left: 20px;
      margin-top: 50px;
      margin-bottom: 25px;
      color: var(--text-primary);
    }
    
    .section-title::before {
      content: "";
      position: absolute;
      left: 0;
      top: 50%;
      transform: translateY(-50%);
      width: 10px;
      height: 10px;
      background-color: var(--accent-color);
      border-radius: 50%;
    }
    
    .content-card {
      background-color: var(--card-bg);
      border-radius: 8px;
      padding: 25px;
      margin-bottom: 30px;
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
      border: 1px solid rgba(100, 255, 218, 0.1);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    
    .content-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 15px 35px rgba(0, 0, 0, 0.3);
    }
    
    .about-list {
      list-style-type: none;
      padding: 0;
    }
    
    .about-list li {
      margin-bottom: 15px;
      display: flex;
      align-items: flex-start;
    }
    
    .about-list li::before {
      content: "→";
      color: var(--accent-color);
      margin-right: 10px;
      font-weight: bold;
    }
    
    .social-links {
      display: flex;
      gap: 15px;
      margin-top: 20px;
    }
    
    .social-links a {
      transition: transform 0.3s ease;
      display: block;
    }
    
    .social-links a:hover {
      transform: translateY(-5px);
    }
    
    .tools-container {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }
    
    .tool-item {
      width: 70px;
      height: 70px;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      background-color: rgba(255, 255, 255, 0.05);
      border-radius: 8px;
      padding: 15px;
      transition: transform 0.3s ease, background-color 0.3s ease;
    }
    
    .tool-item:hover {
      transform: translateY(-5px);
      background-color: rgba(255, 255, 255, 0.1);
    }
    
    .stats-container {
      display: flex;
      justify-content: center;
      margin-top: 20px;
    }
    
    .stats-container img {
      border-radius: 8px;
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
      max-width: 100%;
      height: auto;
    }
    
    .divider {
      height: 4px;
      background: linear-gradient(90deg, transparent, var(--accent-color), transparent);
      margin: 40px 0;
      border-radius: 2px;
    }
    
    @media (max-width: 768px) {
      h1 {
        font-size: 2.5rem;
      }
      
      .section-title {
        font-size: 1.5rem;
      }
      
      .tools-container {
        gap: 10px;
      }
      
      .tool-item {
        width: 50px;
        height: 50px;
        padding: 10px;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="header">
      <h1>Hi 👋, I'm Dilusha Jayanindu Shashipriya</h1>
      <h3>A passionate Full-Stack Developer from Sri Lanka</h3>
      <div class="profile-views">
        <img src="https://komarev.com/ghpvc/?username=dilushajs&label=Profile%20Views&color=0e75b6&style=flat" alt="Profile Views" />
      </div>
    </div>
    
    <div class="divider"></div>
    
    <h2 class="section-title">🚀 About Me</h2>
    <div class="content-card">
      <ul class="about-list">
        <li>🌱 I'm currently learning <strong>Java, OOP, Spring Boot, React</strong></li>
        <li>👯 I'm looking to collaborate on <strong>React Projects</strong></li>
        <li>📫 Reach me at <strong>dilushashashipriya@gmail.com</strong></li>
      </ul>
    </div>
    
    <h2 class="section-title">🌐 Connect with Me</h2>
    <div class="content-card">
      <div class="social-links">
        <a href="https://www.linkedin.com/in/dilusha-jayanindu-shashipriya-270983340" target="_blank">
          <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="40" width="40"/>
        </a>
      </div>
    </div>
    
    <h2 class="section-title">🛠️ Languages & Tools</h2>
    <div class="content-card">
      <div class="tools-container">
        <div class="tool-item">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-original-wordmark.svg" alt="Android" width="40" height="40"/>
        </div>
        <div class="tool-item">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="C" width="40" height="40"/>
        </div>
        <div class="tool-item">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="C++" width="40" height="40"/>
        </div>
        <div class="tool-item">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="CSS3" width="40" height="40"/>
        </div>
        <div class="tool-item">
          <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="Figma" width="40" height="40"/>
        </div>
        <div class="tool-item">
          <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="Git" width="40" height="40"/>
        </div>
        <div class="tool-item">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="HTML5" width="40" height="40"/>
        </div>
        <div class="tool-item">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="Java" width="40" height="40"/>
        </div>
        <div class="tool-item">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" width="40" height="40"/>
        </div>
        <div class="tool-item">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="MySQL" width="40" height="40"/>
        </div>
        <div class="tool-item">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="PHP" width="40" height="40"/>
        </div>
        <div class="tool-item">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="40" height="40"/>
        </div>
        <div class="tool-item">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="React" width="40" height="40"/>
        </div>
        <div class="tool-item">
          <img src="https://www.vectorlogo.zone/logos/springio/springio-icon.svg" alt="Spring Boot" width="40" height="40"/>
        </div>
      </div>
    </div>
    
    <h2 class="section-title">📊 GitHub Stats</h2>
    <div class="content-card">
      <div class="stats-container">
        <img src="https://github-readme-stats.vercel.app/api/top-langs?username=dilushajs&show_icons=true&locale=en&layout=compact&theme=tokyonight" alt="Top Languages" />
      </div>
    </div>
  </div>
</body>
</html>
