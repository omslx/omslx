<!DOCTYPE html>
<html lang="fa">
<head>
  <meta charset="UTF-8">
  <title>Anime GitHub Profile</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: radial-gradient(circle, #1e1e2f, #0d0d1a);
      color: #fff;
      font-family: 'Vazir', sans-serif;
      display: flex;
      align-items: center;
      justify-content: center;
      height: 100vh;
      overflow: hidden;
    }

    .card {
      background: rgba(255, 255, 255, 0.05);
      border: 2px solid #ff70a6;
      border-radius: 20px;
      box-shadow: 0 0 25px #ff70a6;
      padding: 30px;
      text-align: center;
      width: 350px;
      position: relative;
      animation: glow 3s infinite alternate;
    }

    @keyframes glow {
      from { box-shadow: 0 0 15px #ff70a6; }
      to { box-shadow: 0 0 30px #ff70a6, 0 0 60px #ff1493; }
    }

    .profile-img {
      width: 150px;
      border-radius: 50%;
      border: 4px solid #ff70a6;
      box-shadow: 0 0 15px #ff70a6;
      margin-bottom: 20px;
    }

    .typewriter {
      font-size: 22px;
      white-space: nowrap;
      overflow: hidden;
      border-right: 3px solid #fff;
      width: 0;
      animation: typing 4s steps(30, end) forwards, blink 0.7s infinite;
      margin: 0 auto;
    }

    @keyframes typing {
      from { width: 0; }
      to { width: 100%; }
    }

    @keyframes blink {
      50% { border-color: transparent; }
    }

    .langs {
      margin-top: 20px;
      display: flex;
      justify-content: space-around;
    }

    .langs img {
      width: 40px;
      transition: transform 0.3s ease;
    }

    .langs img:hover {
      transform: scale(1.3) rotate(10deg);
      filter: drop-shadow(0 0 5px #ff70a6);
    }
  </style>
</head>
<body>

  <div class="card">
    <img src="https://i.pinimg.com/originals/a4/45/e0/a445e0d7cd07b8a7be03cc2033d30a2b.gif" alt="anime girl" class="profile-img">
    <div class="typewriter">سلام، من [اسم تو] هستم 🌸</div>

    <div class="langs">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kotlin/kotlin-original.svg" alt="Kotlin">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript">
    </div>
  </div>

</body>
</html>
