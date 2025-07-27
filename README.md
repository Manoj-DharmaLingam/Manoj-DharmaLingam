<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>D.S. Manoj Portfolio</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: #0f0f0f;
      color: white;
      margin: 0;
      padding: 0;
      overflow-x: hidden;
      text-align: center;
    }

    .pokeball-container {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      flex-direction: column;
      transition: all 1s ease-in-out;
    }

    .pokeball {
      width: 200px;
      height: 200px;
      cursor: pointer;
      transition: transform 1s ease;
    }

    .content {
      max-width: 900px;
      margin: 0 auto;
      display: none;
      animation: fadeIn 1s ease forwards;
    }

    .open .pokeball {
      transform: scale(0);
    }

    .open .content {
      display: block;
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    summary {
      cursor: pointer;
    }
  </style>
</head>
<body>

<div class="pokeball-container" id="pokeballContainer">
  <img src="hi.png" alt="Pokéball" class="pokeball" id="pokeball" />
</div>

<div class="content" id="mainContent">
  <h1>
    <img src="https://media.giphy.com/media/1APaqOO5QOcwM/giphy.gif" width="120"/>
    <br/>
    Hi, I'm D.S. Manoj
  </h1>

  <p>
    <img src="https://komarev.com/ghpvc/?username=Manoj-DharmaLingam&style=flat-square&color=blue" alt="Profile Views"/>
  </p>

  <p>🎓 <strong>Second-Year Student at AIML – Artificial Intelligent Machine Learning</strong></p>
  <p>📧 <a href="mailto:dsmanoj1543@gmail.com">Email Me</a> for Collaboration, Projects, or Tech Talk 😊</p>

  <h3>🚀 Projects I'm Working On</h3>
  <ul>
    <li>🌾 Wheat Plant Disease Detection using CNN</li>
    <li>🫀 Heart Attack Prediction using Random Forest</li>
  </ul>

  <h3>🌱 What I'm Learning</h3>
  <ul>
    <li>🧠 Deep Learning & CNNs</li>
    <li>🌐 HTML, CSS, JavaScript</li>
    <li>☕ Java, Streamlit</li>
  </ul>

  <h3>🤝 Seeking Help With</h3>
  <ul>
    <li>☁️ Cloud Deployment of ML</li>
    <li>🖼️ Image Classification Optimization</li>
    <li>🧠 LLM Integration</li>
  </ul>

  <h3>💬 Ask Me About</h3>
  <p>ML Projects, Scikit-learn, Python, Collaboration</p>

  <h3>⚡ Fun Fact</h3>
  <blockquote>"I Love Tech and Tech Loves Me – It's Mutual! 💙"</blockquote>

  <h3>📫 Let's Connect</h3>
  <p>
    <a href="https://linkedin.com/in/DsManoj">
      <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="mailto:dsmanoj1543@gmail.com">
      <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
    </a>
  </p>

  <h3>💻 Tech Stack</h3>
  <p>
    <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" />
    <img src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white" />
    <img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" />
    <img src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white" />
    <img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E" />
  </p>

  <h3>📊 GitHub Stats</h3>
  <p>
    <img src="https://github-readme-stats.vercel.app/api?username=Manoj-DharmaLingam&theme=dark&show_icons=true" width="49%">
    <img src="https://nirzak-streak-stats.vercel.app/?user=Manoj-DharmaLingam&theme=dark" width="49%">
  </p>

  <h3>🏆 GitHub Trophies</h3>
  <p>
    <img src="https://github-profile-trophy.vercel.app/?username=Manoj-DharmaLingam&theme=onedark" />
  </p>

  <h3>✍️ Dev Quote</h3>
  <p>
    <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical"/>
  </p>

  <h3>🐍 Contribution Snake</h3>
  <div>
    <img src="https://profile-readme-generator.com/assets/snake.svg" alt="Snake animation" />
  </div>
</div>

<script>
  const pokeball = document.getElementById('pokeball');
  const container = document.getElementById('pokeballContainer');
  const content = document.getElementById('mainContent');

  pokeball.addEventListener('click', () => {
    container.classList.add('open');
  });
</script>

</body>
</html>
