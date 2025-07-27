<style>
  .pokeball {
    width: 100px;
    height: 100px;
    cursor: pointer;
    transition: transform 0.6s ease-in-out;
  }
  .open-animation {
    transform: scaleY(5) scaleX(1.5) rotateX(180deg);
  }
  .hidden-content {
    display: none;
    margin-top: 20px;
  }
  .visible {
    display: block;
  }
</style>

<h1 align="center">
  <img src="https://media.giphy.com/media/1APaqOO5QOcwM/giphy.gif" width="120"/>
  <br/>
  Hi, I'm D.S. Manoj
</h1>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Manoj-DharmaLingam&style=flat-square&color=blue" alt="Profile Views"/>
</p>

<div align="center">
  <img id="pokeball" src="https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/items/poke-ball.png" class="pokeball" onclick="openPokeball()" />
</div>

<div id="content" class="hidden-content">

🎓 <strong>Second-Year Student at AIML – Artificial Intelligent Machine Learning</strong>  
📧 <a href="mailto:dsmanoj1543@gmail.com">Email Me</a> for Collaboration, Projects, or Tech Talk 😊

---

### 🚀 Projects I'm Working On
- 🌾 <strong>Wheat Plant Disease Detection using CNN</strong>
- 🫀 <strong>Heart Attack Prediction using Random Forest</strong>

### 🌱 What I'm Learning
- 🧠 Deep Learning & CNNs  
- 🌐 HTML, CSS, JavaScript  
- ☕ Java, Streamlit  

### 🤝 Seeking Help With
- ☁️ Cloud Deployment of ML  
- 🖼️ Image Classification Optimization  
- 🧠 LLM Integration

### 💬 Ask Me About
- ML Projects, Scikit-learn, Python, Collaboration

### ⚡ Fun Fact
> <em>I Love Tech and Tech Loves Me – It's Mutual! 💙</em>

---

## 📫 Let's Connect
<p align="center">
  <a href="https://linkedin.com/in/DsManoj"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" /></a>  
  <a href="mailto:dsmanoj1543@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

---

## 💻 Tech Stack
<p align="center">
  <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" />
  <img src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E" />
</p>

---

## 📊 GitHub Stats
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Manoj-DharmaLingam&theme=dark&show_icons=true" width="49%" />
  <img src="https://nirzak-streak-stats.vercel.app/?user=Manoj-DharmaLingam&theme=dark" width="49%" />
</p>

---

## 🏆 GitHub Trophies
<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Manoj-DharmaLingam&theme=onedark" />
</p>

---

## ✍️ Dev Quote
<p align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical" />
</p>

---

## 🐍 Contribution Snake
<p align="center">
  <img src="https://profile-readme-generator.com/assets/snake.svg" alt="Snake animation" />
</p>

</div>

<script>
  function openPokeball() {
    const ball = document.getElementById('pokeball');
    const content = document.getElementById('content');
    ball.classList.add('open-animation');
    setTimeout(() => {
      content.classList.add('visible');
    }, 500);
  }
</script>
