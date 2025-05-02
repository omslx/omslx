<!-- FILE: README.md -->
<div align="center">
  <!-- Animated Header -->
  <h1 style="color: #ff1493; text-shadow: 0 0 10px #ff69b4; font-family: 'Arial', sans-serif;">
    ✨ こんにちは！私は <span id="name">[نام شما]</span> です ✨
  </h1>
  
  <!-- Anime Character GIF -->
  <img id="anime-character" src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExcWQ3d3B1a2V5b3V0bWJ2Z2R5d2N4Y2J4eW5xZ2Z6dGQ0d2Q1a3ZqYiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/3oKIPEqDGUULpEU0aQ/giphy.gif" width="250" style="border-radius: 50%; border: 3px solid #ff69b4;"/>
  
  <!-- Skill Badges -->
  <div id="skills-container" style="margin: 20px 0;">
    <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"/>
    <img src="https://img.shields.io/badge/Kotlin-0095D5?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin"/>
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  </div>
</div>

<!-- About Me Section -->
<h2 id="about-me" style="color: #ff69b4;">🎌 درباره من</h2>

<div id="about-content" style="background-color: #1a1a2e; padding: 15px; border-radius: 10px; border-left: 4px solid #ff1493;">
  <p>یک توسعه‌دهنده نرم‌افزار با علاقه به دنیای انیمه و تکنولوژی!</p>
  
  <div id="anime-list">
    <h3 style="color: #ff69b4;">انیمه‌های مورد علاقه:</h3>
    <ul id="anime-favorites" style="list-style-type: none; padding: 0;">
      <!-- Will be filled by JavaScript -->
    </ul>
  </div>
</div>

<!-- Projects Section -->
<h2 style="color: #ff69b4;">🌟 پروژه‌ها</h2>

<div id="projects-container" style="display: flex; flex-wrap: wrap; gap: 15px;">
  <!-- Project cards will be added by JavaScript -->
</div>

<!-- GitHub Stats -->
<h2 style="color: #ff69b4;">📊 آمار گیت‌هاب</h2>

<div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap;">
  <img id="github-stats" src="https://github-readme-stats.vercel.app/api?username=[USERNAME]&show_icons=true&theme=radical" alt="GitHub Stats" style="max-width: 100%;"/>
  <img id="top-langs" src="https://github-readme-stats.vercel.app/api/top-langs/?username=[USERNAME]&layout=compact&theme=tokyonight" alt="Top Languages" style="max-width: 100%;"/>
</div>

<!-- Contact Section -->
<h2 style="color: #ff69b4;">📫 ارتباط با من</h2>

<div id="contact-buttons" style="display: flex; justify-content: center; gap: 10px; flex-wrap: wrap;">
  <a href="https://twitter.com/[YOUR_TWITTER]" target="_blank">
    <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter"/>
  </a>
  <a href="https://linkedin.com/in/[YOUR_LINKEDIN]" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:[YOUR_EMAIL]">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
  </a>
</div>

<!-- Anime Footer -->
<div align="center" style="margin-top: 30px;">
  <img id="anime-footer" src="https://media.giphy.com/media/3o7TKSjRrfIPjeiVyQ/giphy.gif" width="150"/>
</div>

<!-- Custom CSS -->
<style>
  /* Animation for the name */
  @keyframes glow {
    0% { text-shadow: 0 0 5px #ff69b4; }
    50% { text-shadow: 0 0 20px #ff1493, 0 0 30px #ff69b4; }
    100% { text-shadow: 0 0 5px #ff69b4; }
  }
  
  #name {
    animation: glow 2s infinite;
  }
  
  /* Hover effect for anime character */
  #anime-character:hover {
    transform: scale(1.05);
    transition: transform 0.3s ease;
  }
  
  /* Project card styling */
  .project-card {
    background: linear-gradient(145deg, #1a1a2e, #16213e);
    border-radius: 10px;
    padding: 15px;
    width: 300px;
    border-left: 3px solid #ff1493;
    transition: transform 0.3s ease;
  }
  
  .project-card:hover {
    transform: translateY(-5px);
  }
</style>

<!-- JavaScript -->
<script>
  // Set your information
  const userInfo = {
    name: "[نام شما]",
    username: "[USERNAME]",
    animeList: [
      "Attack on Titan", 
      "Jujutsu Kaisen", 
      "Demon Slayer",
      "Naruto",
      "One Piece"
    ],
    projects: [
      {
        name: "Anime Tracker App",
        description: "اپلیکیشن پیگیری انیمه‌های مورد علاقه با Kotlin",
        link: "#"
      },
      {
        name: "Game Engine",
        description: "موتور بازی با الهام از انیمه‌ها با Java",
        link: "#"
      },
      {
        name: "Anime Website",
        description: "وبسایت انیمه با JavaScript و React",
        link: "#"
      }
    ]
  };
  
  // Set the name
  document.getElementById('name').textContent = userInfo.name;
  
  // Fill anime list
  const animeList = document.getElementById('anime-favorites');
  userInfo.animeList.forEach(anime => {
    const li = document.createElement('li');
    li.innerHTML = `🍥 ${anime}`;
    animeList.appendChild(li);
  });
  
  // Create project cards
  const projectsContainer = document.getElementById('projects-container');
  userInfo.projects.forEach(project => {
    const card = document.createElement('div');
    card.className = 'project-card';
    card.innerHTML = `
      <h3 style="color: #ff69b4; margin-top: 0;">${project.name}</h3>
      <p>${project.description}</p>
      <a href="${project.link}" style="color: #ff1493; text-decoration: none;">مشاهده پروژه →</a>
    `;
    projectsContainer.appendChild(card);
  });
  
  // Animate the GitHub stats on hover
  const stats = document.getElementById('github-stats');
  const langs = document.getElementById('top-langs');
  
  [stats, langs].forEach(element => {
    element.style.transition = 'transform 0.3s ease';
    element.addEventListener('mouseenter', () => {
      element.style.transform = 'scale(1.05)';
    });
    element.addEventListener('mouseleave', () => {
      element.style.transform = 'scale(1)';
    });
  });
  
  // Rotate the footer GIF
  const footerGif = document.getElementById('anime-footer');
  let rotation = 0;
  
  setInterval(() => {
    rotation = (rotation + 1) % 360;
    footerGif.style.transform = `rotate(${rotation}deg)`;
  }, 50);
</script>
