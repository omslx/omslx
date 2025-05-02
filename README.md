<!DOCTYPE html>
<html lang="fa">
<head>
  <meta charset="UTF-8">
  <title>پروفایل گیت‌هاب من</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: linear-gradient(135deg, #1e1e2f, #0d0d1a);
      font-family: 'Vazir', sans-serif;
      color: #fff;
      overflow-x: hidden;
    }
    header, footer {
      background-color: #ff70a6;
      text-align: center;
      padding: 20px 0;
      position: relative;
      animation: slideIn 1s ease-in-out;
    }
    @keyframes slideIn {
      from { transform: translateY(-100%); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }
    .container {
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 40px 20px;
    }
    .profile-img {
      width: 120px;
      border-radius: 50%;
      border: 3px solid #ff70a6;
      box-shadow: 0 0 15px #ff70a6;
      margin-bottom: 20px;
      animation: float 4s ease-in-out infinite;
    }
    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
    }
    .typewriter {
      font-size: 24px;
      border-right: 2px solid #fff;
      white-space: nowrap;
      overflow: hidden;
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
      margin-top: 30px;
      display: flex;
      gap: 20px;
    }
    .langs img {
      width: 40px;
      transition: transform 0.3s ease, filter 0.3s ease;
    }
    .langs img:hover {
      transform: scale(1.2);
      filter: drop-shadow(0 0 5px #ff70a6);
    }
    footer {
      margin-top: 40px;
      font-size: 14px;
    }
  </style>
</head>
<body>

  <header>
    <h1>خوش آمدید به پروفایل من</h1>
  </header>

  <div class="container">
    <img class="profile-img" src="https://i.pinimg.com/originals/fd/29/cf/fd29cf4d331a32b1372cdb279d7a0322.gif" alt="Anime Girl" />
    <div class="typewriter">سلام، من [نام شما] هستم</div>

    <div class="langs">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kotlin/kotlin-original.svg" alt="Kotlin">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript">
    </div>
  </div>

  <footer>
    &copy; 2025 پروفایل گیت‌هاب من
  </footer>

</body>
</html>
