<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>پروفایل انیمه‌ای من</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #1a1a2e;
      color: #ffffff;
      max-width: 800px;
      margin: 0 auto;
      padding: 20px;
    }
    .header {
      text-align: center;
      margin-bottom: 30px;
      position: relative;
    }
    .anime-girl {
      width: 200px;
      height: 200px;
      border-radius: 50%;
      border: 5px solid #ff69b4;
      object-fit: cover;
      margin: 0 auto;
      display: block;
      box-shadow: 0 0 20px #ff1493;
    }
    h1 {
      color: #ff69b4;
      font-size: 2.5em;
      margin: 15px 0;
      text-shadow: 0 0 10px #ff1493;
      animation: glow 2s infinite alternate;
    }
    h2 {
      color: #ff69b4;
      border-bottom: 2px solid #ff1493;
      padding-bottom: 5px;
      margin-top: 30px;
    }
    .skills-container {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      justify-content: center;
      margin: 20px 0;
    }
    .skill {
      background: linear-gradient(145deg, #1a1a2e, #16213e);
      padding: 8px 15px;
      border-radius: 20px;
      border: 1px solid #ff69b4;
      font-weight: bold;
    }
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
      gap: 20px;
      margin: 20px 0;
    }
    .project-card {
      background: linear-gradient(145deg, #1a1a2e, #16213e);
      border-radius: 10px;
      padding: 15px;
      border-left: 4px solid #ff69b4;
      transition: transform 0.3s ease;
    }
    .project-card:hover {
      transform: translateY(-5px);
    }
    .anime-gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 15px;
      margin: 20px 0;
    }
    .anime-img {
      width: 120px;
      height: 170px;
      border-radius: 10px;
      object-fit: cover;
      border: 3px solid #ff69b4;
      transition: transform 0.3s ease;
    }
    .anime-img:hover {
      transform: scale(1.1);
    }
    .contact-links {
      display: flex;
      justify-content: center;
      gap: 15px;
      margin-top: 30px;
    }
    .contact-btn {
      padding: 10px 20px;
      border-radius: 5px;
      text-decoration: none;
      font-weight: bold;
      transition: all 0.3s ease;
    }
    .twitter {
      background-color: #1DA1F2;
      color: white;
    }
    .github {
      background-color: #333;
      color: white;
    }
    .email {
      background-color: #D14836;
      color: white;
    }
    @keyframes glow {
      from {
        text-shadow: 0 0 5px #ff69b4;
      }
      to {
        text-shadow: 0 0 20px #ff1493, 0 0 30px #ff69b4;
      }
    }
    .stats-container {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin: 30px 0;
      flex-wrap: wrap;
    }
    .stats-card {
      background: linear-gradient(145deg, #1a1a2e, #16213e);
      padding: 15px;
      border-radius: 10px;
      text-align: center;
      min-width: 200px;
      border: 1px solid #ff69b4;
    }
  </style>
</head>
<body>
  <div class="header">
    <img class="anime-girl" src="https://i.imgur.com/JR4jDfG.gif" alt="Anime Character">
    <h1>[نام شما]</h1>
    <p>توسعه‌دهنده نرم‌افزار | عاشق انیمه | فول‌استک دولوپر</p>
  </div>
  
  <h2>🛠 مهارت‌های فنی</h2>
  <div class="skills-container">
    <span class="skill">Java</span>
    <span class="skill">Kotlin</span>
    <span class="skill">JavaScript</span>
    <span class="skill">React</span>
    <span class="skill">Node.js</span>
    <span class="skill">Android</span>
    <span class="skill">CSS</span>
    <span class="skill">HTML</span>
  </div>
  
  <h2>🌟 پروژه‌های من</h2>
  <div class="projects">
    <div class="project-card">
      <h3>Anime Tracker App</h3>
      <p>اپلیکیشن پیگیری انیمه‌ها با کاتلین و Jetpack Compose</p>
    </div>
    <div class="project-card">
      <h3>Game Engine</h3>
      <p>موتور بازی با جاوا و OpenGL</p>
    </div>
    <div class="project-card">
      <h3>Anime API</h3>
      <p>API داده‌های انیمه با Node.js و Express</p>
    </div>
  </div>
  
  <h2>📊 آمار گیت‌هاب</h2>
  <div class="stats-container">
    <div class="stats-card">
      <h3>تعداد ریپازیتوری‌ها</h3>
      <p>24</p>
    </div>
    <div class="stats-card">
      <h3>تعداد کامیت‌ها</h3>
      <p>1,248</p>
    </div>
    <div class="stats-card">
      <h3>تعداد ستاره‌ها</h3>
      <p>56</p>
    </div>
  </div>
  
  <h2>🎌 انیمه‌های مورد علاقه</h2>
  <div class="anime-gallery">
    <img class="anime-img" src="https://i.imgur.com/8KQ0XJl.png" alt="Attack on Titan">
    <img class="anime-img" src="https://i.imgur.com/JR4jDfG.png" alt="Demon Slayer">
    <img class="anime-img" src="https://i.imgur.com/9KXQwZL.png" alt="Jujutsu Kaisen">
    <img class="anime-img" src="https://i.imgur.com/5XQwZ9L.png" alt="Naruto">
  </div>
  
  <h2>📫 ارتباط با من</h2>
  <div class="contact-links">
    <a href="https://twitter.com/[TWITTER]" class="contact-btn twitter">Twitter</a>
    <a href="https://github.com/[GITHUB]" class="contact-btn github">GitHub</a>
    <a href="mailto:[EMAIL]" class="contact-btn email">Email</a>
  </div>
</body>
</html>
