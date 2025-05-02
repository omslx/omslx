<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My Anime GitHub Profile</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: linear-gradient(to right, #ffe6f0, #e6f0ff);
      font-family: 'Comic Sans MS', cursive, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      overflow: hidden;
    }
    .profile-box {
      background: white;
      border-radius: 25px;
      box-shadow: 0 0 20px rgba(255, 105, 180, 0.6);
      padding: 30px;
      text-align: center;
      position: relative;
      animation: float 3s ease-in-out infinite;
      width: 300px;
    }
    @keyframes float {
      0% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
      100% { transform: translateY(0); }
    }
    .anime-img {
      width: 120px;
      border-radius: 50%;
      border: 3px solid #ff69b4;
      margin-bottom: 20px;
      animation: spin 5s linear infinite;
    }
    @keyframes spin {
      0% { transform: rotate(0deg);}
      100% { transform: rotate(360deg);}
    }
    .name {
      font-size: 24px;
      font-weight: bold;
      color: #ff1493;
      animation: glow 2s ease-in-out infinite alternate;
    }
    @keyframes glow {
      0% { text-shadow: 0 0 5px #ff69b4; }
      100% { text-shadow: 0 0 20px #ff69b4, 0 0 30px #ff69b4; }
    }
    .languages {
      margin-top: 20px;
      display: flex;
      justify-content: space-around;
    }
    .languages img {
      width: 40px;
      transition: transform 0.3s;
    }
    .languages img:hover {
      transform: scale(1.2);
    }
    .tag {
      font-size: 14px;
      margin-top: 5px;
      color: #555;
    }
  </style>
</head>
<body>

  <div class="profile-box">
    <img class="anime-img" src="https://i.pinimg.com/originals/a4/45/e0/a445e0d7cd07b8a7be03cc2033d30a2b.gif" alt="anime girl" />
    <div class="name">سلام، من [اسمت اینجا]</div>
    <div class="tag">برنامه‌نویس عاشق انیمه 💻✨</div>
    <div class="languages">
      <div>
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java">
      </div>
      <div>
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kotlin/kotlin-original.svg" alt="Kotlin">
      </div>
      <div>
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript">
      </div>
    </div>
  </div>

</body>
</html>
