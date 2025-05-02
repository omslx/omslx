<!DOCTYPE html>
<html lang="fa">
<head>
  <meta charset="UTF-8">
  <title>Kawaii GitHub Profile</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: #0d0b1f;
      color: #fff;
      font-family: 'Comic Neue', cursive;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      overflow: hidden;
    }
    .card {
      background: rgba(255, 255, 255, 0.05);
      border: 1px solid #ff9de2;
      border-radius: 16px;
      padding: 25px;
      text-align: center;
      box-shadow: 0 0 20px #ff8ed6;
      animation: float 4s ease-in-out infinite;
      width: 280px;
    }
    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
    }
    .pfp {
      width: 90px;
      border-radius: 50%;
      border: 2px solid #ff6fcf;
      box-shadow: 0 0 15px #ff6fcf;
      margin-bottom: 15px;
    }
    .name {
      font-size: 18px;
      color: #ffc0f9;
      text-shadow: 0 0 8px #ff8ed6;
      margin-bottom: 10px;
      white-space: nowrap;
      overflow: hidden;
      border-right: 2px solid #fff;
      width: 0;
      animation: typing 3s steps(30, end) forwards, blink 0.7s infinite;
    }
    @keyframes typing {
      from { width: 0; }
      to { width: 100%; }
    }
    @keyframes blink {
      50% { border-color: transparent; }
    }
    .langs {
      margin-top: 15px;
      display: flex;
      justify-content: center;
      gap: 12px;
    }
    .langs img {
      width: 28px;
      height: 28px;
      transition: transform 0.2s ease, filter 0.2s ease;
    }
    .langs img:hover {
      transform: scale(1.3);
      filter: drop-shadow(0 0 6px #ff8ed6);
    }
  </style>
</head>
<body>

  <div class="card">
    <img class="pfp" src="https://i.pinimg.com/originals/fd/29/cf/fd29cf4d331a32b1372cdb279d7a0322.gif" alt="anime girl" />
    <div class="name">✧ من [اسم تو] هستم ✧</div>
    <div class="langs">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kotlin/kotlin-original.svg" alt="Kotlin">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript">
    </div>
  </div>

</body>
</html>
