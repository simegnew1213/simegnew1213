<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Simegnew Aregahegn - Profile</title>

  <link href="https://fonts.googleapis.com/css2?family=Fira+Code:wght@400;600&family=Syne:wght@700;800&display=swap" rel="stylesheet"/>

  <style>
    body {
      font-family: sans-serif;
      background: #0f172a;
      color: #e2e8f0;
      max-width: 820px;
      margin: 0 auto;
      padding: 24px;
    }

    h1 { text-align: center; font-size: 2rem; color: #f1f5f9; }
    h2 { color: #38bdf8; }
    h3 { text-align: center; color: #94a3b8; }
    p { text-align: center; }
    hr { border-color: #334155; margin: 28px 0; }

    /* ===== ANIMATIONS ===== */

    .greeting-line {
      display: inline-block;
      opacity: 0;
      transform: translateY(24px);
      animation: fadeSlideUp 0.7s ease forwards 0.2s;
    }

    .wave-emoji {
      display: inline-block;
      animation: waveHand 1.8s ease-in-out 1s infinite;
      transform-origin: 70% 80%;
    }

    .name-text {
      font-family: 'Syne', sans-serif;
      font-weight: 800;
      font-size: 1.15em;
      display: inline-block;
      opacity: 0;
      animation: fadeSlideUp 0.7s ease forwards 0.55s;
    }

    .name-text span.letter {
      display: inline-block;
      color: #38bdf8;
      opacity: 0;
      transform: translateY(18px) scale(0.8);
      animation: letterPop 0.45s cubic-bezier(.34,1.56,.64,1) forwards;
    }

    .animated-h1 {
      position: relative;
      display: inline-block;
    }

    .animated-h1::after {
      content: '';
      position: absolute;
      bottom: -4px;
      left: 0;
      width: 100%;
      height: 3px;
      background: linear-gradient(90deg, transparent, #38bdf8, #818cf8, #38bdf8, transparent);
      background-size: 200% 100%;
      border-radius: 2px;
      opacity: 0;
      animation: shimmerLine 2.5s linear 1.4s infinite, fadeIn 0.5s ease 1.2s forwards;
    }

    .subtitle-animated {
      overflow: hidden;
      white-space: nowrap;
      width: 0;
      animation: typeReveal 1.8s steps(60, end) forwards 1.6s;
      margin: 0 auto;
      display: inline-block;
    }

    @keyframes fadeSlideUp {
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes waveHand {
      0%,60%,100% { transform: rotate(0deg); }
      10%,30% { transform: rotate(18deg); }
      20% { transform: rotate(-8deg); }
      40% { transform: rotate(14deg); }
      50% { transform: rotate(-4deg); }
    }

    @keyframes letterPop {
      to { opacity: 1; transform: translateY(0) scale(1); }
    }

    @keyframes shimmerLine {
      0% { background-position: 200% 0; }
      100% { background-position: -200% 0; }
    }

    @keyframes fadeIn {
      to { opacity: 1; }
    }

    @keyframes typeReveal {
      to { width: 100%; }
    }
  </style>
</head>

<body>

<!-- FLAG -->
<p>
  <img src="https://upload.wikimedia.org/wikipedia/commons/7/71/Flag_of_Ethiopia.svg" width="100">
</p>

<!-- HEADER -->
<h1 class="animated-h1">
  <span class="greeting-line">Hi there <span class="wave-emoji">👋</span>, I'm</span>
  <span class="name-text" id="nameSpan">&nbsp;SIMEGNEW AREGAHEGN</span>
</h1>

<h3>
  <span class="subtitle-animated">
    💻 Website Developer | HTML & CSS Enthusiast | Lifelong Learner | AI & Machine Learning Explorer
  </span>
</h3>

<!-- GIF -->
<p>
  <img src="https://media.giphy.com/media/L05HgB2h6qICDs5Sms/giphy.gif" width="400">
</p>

<h3>🤖 Exploring AI, Machine Learning, and Deep Learning</h3>
<p>
  From building predictive models to experimenting with neural networks — I love turning data into insights.
</p>

<!-- SKILLS ICONS -->
<p>
  <img src="https://img.icons8.com/color/48/html-5--v1.png"/>
  <img src="https://img.icons8.com/color/48/css3.png"/>
  <img src="https://img.icons8.com/color/48/javascript--v1.png"/>
  <img src="https://img.icons8.com/color/48/java-coffee-cup-logo--v1.png"/>
  <img src="https://img.icons8.com/color/48/c-plus-plus-logo.png"/>
  <img src="https://img.icons8.com/color/48/python--v1.png"/>
  <img src="https://img.icons8.com/color/48/r-project.png"/>
</p>

<hr/>

<h2>🔗 Connect with Me</h2>
<p>
  <a href="mailto:simegnaregahagn@gmail.com">
    <img src="https://img.shields.io/badge/email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://www.linkedin.com/in/simegnewaregahegn000" target="_blank">
    <img src="https://img.shields.io/badge/linkedin-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://www.facebook.com/simegnaregahagn" target="_blank">
    <img src="https://img.shields.io/badge/facebook-4267B2?style=for-the-badge&logo=facebook&logoColor=white"/>
  </a>
</p>

<hr/>

<h2>👨‍💻 About Me</h2>
<ul>
  <li>🌍 Based in Ethiopia</li>
  <li>💻 2nd-year Data Science student & web developer</li>
  <li>🔭 Learning JavaScript, Python, Django, ML</li>
  <li>🌱 Exploring AI, Deep Learning & Full-stack</li>
  <li>🤝 Open to collaboration</li>
</ul>

<hr/>

<h2>🛠️ Skills</h2>
<p>
  <img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
</p>

<hr/>

<h2>🏆 Projects</h2>
<div align="center">
  <a href="https://your-website-project-link.com" target="_blank">
    <img src="https://img.icons8.com/fluency/100/web-design.png"/>
  </a>
  <a href="https://github.com/simegnew1213/ai-project1" target="_blank">
    <img src="https://img.icons8.com/fluency/100/artificial-intelligence.png"/>
  </a>
</div>

<p>
  More on <a href="https://github.com/simegnew1213">GitHub</a>
</p>

<hr/>

<h2>⚡ Fun Fact</h2>
<blockquote>
  <em>"I build websites like poetry and train models like puzzles."</em>
</blockquote>

<hr/>

<h2>📱 Contact</h2>
<ul>
  <li>Email: simegnaregahagn@gmail.com</li>
  <li>Phone: +251 903269180</li>
</ul>

<!-- NAME ANIMATION SCRIPT -->
<script>
(function () {
  const nameSpan = document.getElementById('nameSpan');
  const fullName = '\u00a0SIMEGNEW AREGAHEGN';
  nameSpan.textContent = '';

  [...fullName].forEach((ch, i) => {
    if (ch === ' ' || ch === '\u00a0') {
      nameSpan.appendChild(document.createTextNode(ch));
      return;
    }
    const span = document.createElement('span');
    span.classList.add('letter');
    span.textContent = ch;
    span.style.animationDelay = (0.65 + i * 0.055) + 's';
    nameSpan.appendChild(span);
  });
})();
</script>

</body>
</html>
