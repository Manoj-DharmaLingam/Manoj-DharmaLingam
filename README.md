<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>D.S. Manoj – Portfolio</title>
  <style>
    body {
      background-color: #000;
      color: white;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      text-align: center;
      margin: 0;
      padding: 0;
    }

    .pokeball-container {
      position: relative;
      top: 10vh;
      cursor: pointer;
      transition: transform 0.6s ease;
    }

    .pokeball-container img {
      width: 220px;
      transition: transform 1s ease;
    }

    .content {
      display: none;
      padding: 2em;
      max-width: 1000px;
      margin: 0 auto;
    }

    .reveal .content {
      display: block;
      animation: fadeIn 2s;
    }

    .reveal .pokeball-container img {
      transform: rotateX(180deg) scale(1.5);
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
  </style>
</head>
<body>

<div class="pokeball-container" onclick="toggleReveal()">
  <img src="/mnt/data/hi.png" alt="Pokeball" id="pokeball">
</div>

<div class="content" id="portfolioContent">
  <h1>Hi, I'm D.S. Manoj</h1>

  <p>
    <img src="https://komarev.com/ghpvc/?username=Manoj-DharmaLingam&style=flat-square&color=blue" alt="Profile Views"/>
  </p>

  <p><strong>🎓 Second-Year Student at AIML – Artificial Intelligent Machine Learning</strong></p>
  <p>📧 <a href="mailto:dsmanoj1543@gmail.com">Email Me</a> for Collaboration, Projects, or Tech Talk 😊</p>

  <h2>🚀 Projects I'm Working On</h2>
  <ul>
    <li>🌾 Wheat Plant Disease Detection using CNN</li>
    <li>🫀 Heart Attack Prediction using Random Forest</li>
  </ul>

  <h2>🌱 What I'm Learning</h2>
  <ul>
    <li>🧠 Deep Learning & CNNs</li>
    <li>🌐 HTML, CSS, JavaScript</li>
    <li>☕ Java, Streamlit</li>
  </ul>

  <h2>🤝 Seeking Help With</h2>
  <ul>
    <li>☁️ Cloud Deployment of ML</li>
    <li>🖼️ Image Classification Optimization</li>
    <li>🧠 LLM Integration</li>
  </ul>

  <h2>💬 Ask Me About</h2>
  <p>ML Projects, Scikit-learn, Python, Collaboration</p>

  <h2>⚡ Fun Fact</h2>
  <blockquote>"I Love Tech and Tech Loves Me – It's Mutual! 💙"</blockquote>

  <h2>📫 Let's Connect</h2>
  <p>
    <a href="https://linkedin.com/in/DsManoj" target="_blank">LinkedIn</a> |
    <a href="mailto:dsmanoj1543@gmail.com">Gmail</a>
  </p>

  <h2>💻 Tech Stack</h2>
  <p>
    <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54"/>
    <img src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white"/>
    <img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white"/>
    <img src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white"/>
    <img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/>
  </p>

  <h2>📊 GitHub Stats</h2>
  <p>
    <img src="https://github-readme-stats.vercel.app/api?username=Manoj-DharmaLingam&theme=dark&show_icons=true" width="49%">
    <img src="https://nirzak-streak-stats.vercel.app/?user=Manoj-DharmaLingam&theme=dark" width="49%">
  </p>

  <h2>🏆 GitHub Trophies</h2>
  <p>
    <img src="https://github-profile-trophy.vercel.app/?username=Manoj-DharmaLingam&theme=onedark" />
  </p>

  <h2>✍️ Dev Quote</h2>
  <p>
    <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical"/>
  </p>
</div>

<script>
  function toggleReveal() {
    document.body.classList.toggle('reveal');
  }
</script>

</body>
</html>
