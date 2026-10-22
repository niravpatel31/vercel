<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>A Message From My Heart ❤️</title>
  <style>
   {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      min-height: 100vh;
      background: linear-gradient(135deg, #ff9a9e 0%, #fecfef 99%, #fecfef 100%);
      font-family: 'Poppins', 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 20px;
      overflow-x: hidden;
      position: relative;
    }

    /* Floating Background Hearts */
    .heart-bg {
      position: fixed;
      font-size: 24px;
      animation: floatUp 6s linear infinite;
      z-index: 0;
      opacity: 0.6;
      pointer-events: none;
    }
    @keyframes floatUp {
      0% {
        transform: translateY(105vh) scale(0.6) rotate(0deg);
        opacity: 0;
      }
      50% {
        opacity: 0.8;
      }
      100% {
        transform: translateY(-10vh) scale(1.2) rotate(360deg);
        opacity: 0;
      }
    }

    /* Envelope / Card Container */
    .card-container {
      background: rgba(255, 255, 255, 0.95);
      backdrop-filter: blur(8px);
      max-width: 520px;
      width: 100%;
      border-radius: 24px;
      padding: 30px;
      box-shadow: 0 20px 40px rgba(255, 75, 110, 0.25);
      text-align: center;
      position: relative;
      z-index: 10;
      border: 2px solid #ffe3ec;
      animation: popIn 0.8s cubic-bezier(0.175, 0.885, 0.32, 1.275);
    }
    @keyframes popIn {
      0% { transform: scale(0.7); opacity: 0; }
      100% { transform: scale(1); opacity: 1; }
    }

    .sticker-header {
      font-size: 50px;
      margin-bottom: 10px;
      animation: pulse 1.5s infinite;
    }
    @keyframes pulse {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.15); }
    }

    .gif-container {
      margin: 15px auto;
      border-radius: 16px;
      overflow: hidden;
      max-width: 250px;
      box-shadow: 0 8px 18px rgba(0,0,0,0.1);
    }
    .gif-container img {
      width: 100%;
      display: block;
    }

    h1 {
      color: #e63946;
      font-size: 26px;
      margin-bottom: 8px;
    }
    h2 {
      color: #ff6b81;
      font-size: 16px;
      font-weight: 500;
      margin-bottom: 20px;
    }

    /* Letter Body */
    .letter {
      background: #fff8fa;
      border-left: 4px solid #ff4d6d;
      padding: 18px;
      border-radius: 12px;
      text-align: left;
      font-size: 15px;
      line-height: 1.7;
      color: #4a4a4a;
      margin-bottom: 20px;
      box-shadow: inset 0 2px 6px rgba(0,0,0,0.03);
    }
    .letter p {
      margin-bottom: 12px;
    }

    /* Love Meter */
    .love-meter-title {
      font-size: 14px;
      font-weight: 600;
      color: #ff477e;
      margin-bottom: 8px;
    }
    .progress-bar {
      background: #ffd6e0;
      border-radius: 20px;
      height: 18px;
      overflow: hidden;
      position: relative;
      margin-bottom: 20px;
    }
    .progress-fill {
      width: 100%;
      height: 100%;
      background: linear-gradient(90deg, #ff758c, #ff4d6d);
      border-radius: 20px;
      animation: fillMeter 2s ease-out;
    }
    @keyframes fillMeter {
      0% { width: 0%; }
      100% { width: 100%; }
    }

    /* Interactive Buttons */
    .btn-container {
      display: flex;
      flex-direction: column;
      gap: 12px;
    }
    .btn {
      padding: 12px 25px;
      border: none;
      border-radius: 50px;
      font-size: 16px;
      font-weight: 600;
      cursor: pointer;
      transition: all 0.3s ease;
    }
    .btn-forgive {
      background: linear-gradient(45deg, #ff477e, #ff5e62);
      color: white;
      box-shadow: 0 6px 15px rgba(255, 71, 126, 0.4);
    }
    .btn-forgive:hover {
      transform: translateY(-2px);
      box-shadow: 0 10px 20px rgba(255, 71, 126, 0.5);
    }

    /* Celebration Overlay */
    #celebration {
      display: none;
      margin-top: 15px;
      padding: 15px;
      border-radius: 12px;
      background: #e8f5e9;
      color: #2e7d32;
      font-weight: 600;
      font-size: 16px;
      animation: popIn 0.5s ease;
    }
  </style>
</head>
<body>

  <!-- Floating Hearts Container -->
  <div id="heart-spawner"></div>

  <div class="card-container">
    <div class="sticker-header">🥺💐❤️🩹</div>
    
    <h1>I'm Truly Sorry, My Love</h1>
    <h2>You mean the world to me ✨</h2>

    <!-- Cute GIF -->
    <div class="gif-container">
      <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExbnZ5bzZreW92Mzl5OXg5dGZkY3I1cTF2dnU5b3Z1dG56dDFpdWtzZSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/9Y6n9TR7U07ew/giphy.gif" alt="Cute Apology GIF" />
    </div>

    <!-- Apology Letter -->
    <div class="letter">
      <p><strong>My Dearest,</strong></p>
      <p>
        I want to sincerely apologize from the bottom of my heart for hurting you. Seeing you upset because of me breaks my heart more than words can say.
      </p>
      <p>
        My intentions are never to make you feel bad, but I know I made a mistake. You are my favorite person, my safest place, and my greatest blessing. 
      </p>
      <p>
        I promise to listen better, understand deeper, and cherish every single moment with you. Please forgive me? 🥺
      </p>
      <p><strong>Forever & Always Yours, ❤️</strong></p>
    </div>

    <!-- Love Meter -->
    <div class="love-meter-title">How Much I Love You: <strong>∞ / 100%</strong></div>
    <div class="progress-bar">
      <div class="progress-fill"></div>
    </div>

    <!-- Interactive Actions -->
    <div class="btn-container">
      <button class="btn btn-forgive" onclick="forgiveMe()">I Forgive You 💕</button>
    </div>

    <div id="celebration">
      🎉 Thank you, my love! I promise to make you smile every day! 🐻💖
    </div>
  </div>

  <script>
    // Create floating emojis in background
    const emojis = ['💖', '🌸', '✨', '🥺', '💌', '🧸', '🌹'];
    const spawner = document.getElementById('heart-spawner');

    function createFloatingElement() {
      const el = document.createElement('div');
      el.className = 'heart-bg';
      el.innerText = emojis[Math.floor(Math.random() * emojis.length)];
      el.style.left = Math.random() * 100 + 'vw';
      el.style.animationDuration = (Math.random() * 3 + 4) + 's';
      spawner.appendChild(el);

      setTimeout(() => {
        el.remove();
      }, 7000);
    }

    setInterval(createFloatingElement, 400);

    // Button click interaction
    function forgiveMe() {
      const banner = document.getElementById('celebration');
      banner.style.display = 'block';

      // Confetti effect using emojis
      for (let i = 0; i < 30; i++) {
        setTimeout(createFloatingElement, i * 50);
      }
    }
  </script>
</body>
</html>
