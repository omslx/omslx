<!-- File: README.md -->
<div align="center">
  <h1>
    <a href="https://git.io/typing-svg">
      <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=4000&pause=1000&color=00F72D&center=true&vCenter=true&width=500&height=60&lines=%D8%AE%D9%88%D8%B4+%D8%A2%D9%85%D8%AF%DB%8C%D8%AF+%D8%A8%D9%87+%D8%AC%D9%87%D8%A7%D9%86+mslx;%D8%AA%D9%88%D8%B3%D8%B9%D9%87+%D8%AF%D9%87%D9%86%D8%AF%D9%87+%D9%86%D9%88%DA%AF%D8%B1%D8%A7%D9%86;%D9%85%D8%AA%D8%AE%D8%B5%D8%B5+%D9%87%DA%A9+%D9%88+%D8%A7%D9%85%D9%86%DB%8C%D8%AA;%D8%A8%D8%B1%D9%86%D8%AF%D9%87+%D9%85%D8%B3%D8%A7%D8%A8%D9%82%D8%A7%D8%AA+%D9%87%DA%A9%D8%A7%D8%AA%D9%88%D9%86" alt="Typing SVG" />
    </a>
  </h1>

  <!-- Particle.js Animation -->
  <canvas id="particles-js" width="100%" height="150" style="border-radius: 10px; margin: 20px 0;"></canvas>
  
  <script src="https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>
  <script>
    particlesJS("particles-js", {
      "particles": {
        "number": { "value": 80, "density": { "enable": true, "value_area": 800 } },
        "color": { "value": "#00ff00" },
        "shape": { "type": "circle" },
        "opacity": { "value": 0.5, "random": true },
        "size": { "value": 3, "random": true },
        "line_linked": { "enable": true, "distance": 150, "color": "#00ff00", "opacity": 0.4, "width": 1 },
        "move": { "enable": true, "speed": 3, "direction": "none", "random": true, "straight": false, "out_mode": "out" }
      },
      "interactivity": {
        "detect_on": "canvas",
        "events": {
          "onhover": { "enable": true, "mode": "repulse" },
          "onclick": { "enable": true, "mode": "push" },
          "resize": true
        },
        "modes": { "repulse": { "distance": 100, "duration": 0.4 } }
      }
    });
  </script>

  <!-- 3D Card Animation -->
  <div class="card-container" style="perspective: 1000px; width: 300px; height: 200px; margin: 30px auto;">
    <div class="card" style="width: 100%; height: 100%; position: relative; transform-style: preserve-3d; transition: transform 1s; background: linear-gradient(45deg, #0f2027, #203a43, #2c5364); border-radius: 15px; box-shadow: 0 10px 30px rgba(0, 247, 45, 0.5);">
      <div style="position: absolute; width: 100%; height: 100%; backface-visibility: hidden; display: flex; flex-direction: column; justify-content: center; align-items: center; color: white; padding: 20px; box-sizing: border-box;">
        <h3 style="color: #00F72D; margin-bottom: 10px;">mslx</h3>
        <p style="text-align: center;">Hacker | Developer | Security Expert</p>
        <div style="display: flex; margin-top: 15px;">
          <span style="background: rgba(0, 247, 45, 0.2); padding: 5px 10px; border-radius: 20px; margin: 0 5px; font-size: 12px;">Python</span>
          <span style="background: rgba(0, 247, 45, 0.2); padding: 5px 10px; border-radius: 20px; margin: 0 5px; font-size: 12px;">JavaScript</span>
        </div>
      </div>
    </div>
  </div>

  <script>
    document.querySelector('.card-container').addEventListener('mousemove', (e) => {
      const xAxis = (window.innerWidth / 2 - e.pageX) / 25;
      const yAxis = (window.innerHeight / 2 - e.pageY) / 25;
      document.querySelector('.card').style.transform = `rotateY(${xAxis}deg) rotateX(${yAxis}deg)`;
    });
  </script>
</div>

## 🔥 مهارت‌های من
<div align="center" style="display: grid; grid-template-columns: repeat(auto-fill, minmax(100px, 1fr)); gap: 15px; margin: 20px 0;">
  <div class="skill" style="background: rgba(0, 0, 0, 0.3); padding: 15px; border-radius: 10px; transition: all 0.3s; border: 1px solid rgba(0, 247, 45, 0.3);">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="40" height="40" />
    <p>Python</p>
  </div>
  <!-- Add more skills in same pattern -->
</div>

<script>
  document.querySelectorAll('.skill').forEach(skill => {
    skill.addEventListener('mouseover', () => {
      skill.style.transform = 'translateY(-5px)';
      skill.style.boxShadow = '0 5px 15px rgba(0, 247, 45, 0.5)';
    });
    skill.addEventListener('mouseout', () => {
      skill.style.transform = 'none';
      skill.style.boxShadow = 'none';
    });
  });
</script>

## 🚀 پروژه‌های برجسته
<div class="projects" style="display: grid; grid-template-columns: repeat(auto-fill, minmax(300px, 1fr)); gap: 20px; margin: 30px 0;">
  <div class="project" style="background: rgba(0, 0, 0, 0.3); border-radius: 10px; overflow: hidden; transition: all 0.3s; border: 1px solid rgba(0, 247, 45, 0.3);">
    <div style="height: 150px; background: linear-gradient(45deg, #0f2027, #203a43); display: flex; justify-content: center; align-items: center;">
      <h3 style="color: #00F72D;">پروژه نفوذ</h3>
    </div>
    <div style="padding: 15px;">
      <p>یک ابزار پیشرفته برای تست نفوذ و امنیت</p>
      <div style="display: flex; margin-top: 15px;">
        <span style="background: rgba(0, 247, 45, 0.2); padding: 3px 8px; border-radius: 20px; margin-right: 5px; font-size: 10px;">Python</span>
        <span style="background: rgba(0, 247, 45, 0.2); padding: 3px 8px; border-radius: 20px; font-size: 10px;">Security</span>
      </div>
    </div>
  </div>
  <!-- Add more projects in same pattern -->
</div>

<script>
  document.querySelectorAll('.project').forEach(project => {
    project.addEventListener('mouseover', () => {
      project.style.transform = 'scale(1.03)';
      project.style.boxShadow = '0 10px 20px rgba(0, 247, 45, 0.3)';
    });
    project.addEventListener('mouseout', () => {
      project.style.transform = 'none';
      project.style.boxShadow = 'none';
    });
  });
</script>

## 📊 آمار گیت‌هاب
<div align="center" style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 20px; margin: 30px 0;">
  <img src="https://github-readme-stats.vercel.app/api?username=mslx&show_icons=true&theme=dark&bg_color=0d1117&title_color=00F72D&icon_color=00F72D&text_color=ffffff" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=mslx&theme=dark&background=0d1117&stroke=00F72D&ring=00F72D&fire=00F72D&currStreakNum=ffffff&sideNums=ffffff&currStreakLabel=00F72D" />
</div>

## 🌐 ارتباط با من
<div align="center" style="margin: 30px 0;">
  <a href="https://t.me/mslx" style="display: inline-block; margin: 0 10px;">
    <img src="https://img.icons8.com/color/48/000000/telegram-app--v1.png" width="40" />
  </a>
  <a href="mailto:mslx@protonmail.com" style="display: inline-block; margin: 0 10px;">
    <img src="https://img.icons8.com/color/48/000000/protonmail.png" width="40" />
  </a>
  <a href="https://twitter.com/mslx" style="display: inline-block; margin: 0 10px;">
    <img src="https://img.icons8.com/color/48/000000/twitter--v1.png" width="40" />
  </a>
</div>

<!-- Matrix Rain Animation -->
<div align="center" style="margin: 50px 0; position: relative; height: 100px; overflow: hidden;">
  <canvas id="matrix" style="width: 100%; height: 100%; border-radius: 10px;"></canvas>
</div>

<script>
  const canvas = document.getElementById('matrix');
  const ctx = canvas.getContext('2d');
  
  canvas.width = canvas.offsetWidth;
  canvas.height = canvas.offsetHeight;
  
  const katakana = 'アァカサタナハマヤャラワガザダバパイィキシチニヒミリヰギジヂビピウゥクスツヌフムユュルグズブヅプエェケセテネヘメレヱゲゼデベペオォコソトノホモヨョロヲゴゾドボポヴッン';
  const latin = 'ABCDEFGHIJKLMNOPQRSTUVWXYZ';
  const nums = '0123456789';
  const symbols = '!"#$%&\'()*+,-./:;<=>?@[\\]^_`{|}~';
  
  const alphabet = katakana + latin + nums + symbols;
  
  const fontSize = 16;
  const columns = canvas.width / fontSize;
  
  const rainDrops = [];
  
  for (let x = 0; x < columns; x++) {
    rainDrops[x] = 1;
  }
  
  const draw = () => {
    ctx.fillStyle = 'rgba(0, 0, 0, 0.05)';
    ctx.fillRect(0, 0, canvas.width, canvas.height);
    
    ctx.fillStyle = '#00F72D';
    ctx.font = fontSize + 'px monospace';
    
    for (let i = 0; i < rainDrops.length; i++) {
      const text = alphabet.charAt(Math.floor(Math.random() * alphabet.length));
      ctx.fillText(text, i * fontSize, rainDrops[i] * fontSize);
      
      if (rainDrops[i] * fontSize > canvas.height && Math.random() > 0.975) {
        rainDrops[i] = 0;
      }
      rainDrops[i]++;
    }
  };
  
  setInterval(draw, 30);
</script>
