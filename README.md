<style>
  * {
    box-sizing: border-box;
  }

  body {
    margin: 0;
    padding: 0;
    min-height: 100vh;
    background: linear-gradient(to bottom right, #000428, #004e92);
    overflow-x: hidden;
    font-family: 'Poppins', sans-serif;
    color: #ffd700;
    text-align: center;
    display: flex;
    flex-direction: column;
  }

  .container {
    padding: 2rem 1rem;
    display: none;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 100%;
  }

  .intro-card {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    min-height: 100vh;
    padding: 1rem;
    color: #fff;
    font-size: 1.5em;
    background: rgba(0,0,0,0.6);
    backdrop-filter: blur(10px);
    animation: fadeIn 2s ease-in-out;
  }

  .intro-card h1 {
    font-size: 3em;
    margin-bottom: 0.5em;
    text-shadow: 0 0 20px #ffd700;
  }

  .intro-card p {
    font-size: 1.2em;
    color: #ffd700;
  }

  h1 {
    font-size: 2.5em;
    color: #fff;
    text-shadow: 0 0 20px #ffd700, 0 0 40px #ffd700;
    animation: pulse 2s infinite;
    margin: 0.5em 0;
  }

  p {
    font-size: 1.1em;
    color: #fff;
    margin-top: 1.2em;
    padding: 0 1rem;
    max-width: 90vw;
    line-height: 1.7em;
    font-weight: bold;
  }

  .glow {
    animation: glow 3s ease-in-out infinite alternate;
  }

  @keyframes glow {
    from {
      text-shadow: 0 0 10px #ffd700, 0 0 20px #ffd700;
    }
    to {
      text-shadow: 0 0 30px #ffd700, 0 0 60px #ffd700;
    }
  }

  @keyframes pulse {
    0% { transform: scale(1); }
    50% { transform: scale(1.05); }
    100% { transform: scale(1); }
  }

  @keyframes fadeIn {
    from { opacity: 0; }
    to { opacity: 1; }
  }

  .confetti {
    position: fixed;
    width: 100%;
    height: 100%;
    pointer-events: none;
    top: 0;
    left: 0;
  }

  button {
    margin-top: 1.5em;
    padding: 0.7em 2em;
    font-size: 1.1em;
    border: none;
    border-radius: 12px;
    background-color: #ffd700;
    color: #000;
    font-weight: bold;
    cursor: pointer;
    transition: transform 0.3s;
  }

  button:hover {
    transform: scale(1.05);
  }

  @media (max-width: 600px) {
    .intro-card h1 {
      font-size: 2em;
    }

    .intro-card p {
      font-size: 1em;
    }

    h1 {
      font-size: 2em;
    }

    p {
      font-size: 1em;
    }

    button {
      font-size: 1em;
      padding: 0.6em 1.5em;
    }
  }
</style>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Happy Birthday Sapna</title>
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Poppins:wght@700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      padding: 0;
      min-height: 100vh;
      background: linear-gradient(to bottom right, #000428, #004e92);
      overflow-x: hidden;
      font-family: 'Poppins', sans-serif;
      color: #ffd700;
      text-align: center;
    }

    .container {
      padding: 4rem 2rem;
      display: none;
      flex-direction: column;
      align-items: center;
      justify-content: center;
    }

    .intro-card {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      color: #fff;
      font-size: 2em;
      background: rgba(0,0,0,0.6);
      backdrop-filter: blur(10px);
      animation: fadeIn 2s ease-in-out;
    }

    .intro-card h1 {
      font-size: 4em;
      margin-bottom: 0.5em;
      text-shadow: 0 0 20px #ffd700;
    }

    .intro-card p {
      font-size: 1.5em;
      color: #ffd700;
    }

    h1 {
      font-size: 4em;
      color: #fff;
      text-shadow: 0 0 20px #ffd700, 0 0 40px #ffd700;
      animation: pulse 2s infinite;
    }

    p {
      font-size: 1.4em;
      color: #fff;
      margin-top: 1.5em;
      max-width: 800px;
      line-height: 1.8em;
      font-weight: bold;
    }

    .glow {
      animation: glow 3s ease-in-out infinite alternate;
    }

    @keyframes glow {
      from {
        text-shadow: 0 0 10px #ffd700, 0 0 20px #ffd700;
      }
      to {
        text-shadow: 0 0 30px #ffd700, 0 0 60px #ffd700;
      }
    }

    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.05); }
      100% { transform: scale(1); }
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    .confetti {
      position: fixed;
      width: 100%;
      height: 100%;
      pointer-events: none;
      top: 0;
      left: 0;
    }

    button {
      margin-top: 1.5em;
      padding: 0.7em 2em;
      font-size: 1.2em;
      border: none;
      border-radius: 12px;
      background-color: #ffd700;
      color: #000;
      font-weight: bold;
      cursor: pointer;
      transition: transform 0.3s;
    }

    button:hover {
      transform: scale(1.05);
    }
  </style>
</head>
<body>
  <audio autoplay loop>
    <source src="https://cdn.pixabay.com/download/audio/2022/11/06/audio_4c9750cece.mp3?filename=birthday-cake-126735.mp3" type="audio/mpeg" />
  </audio>

  <div class="intro-card" id="intro">
    <h1 class="glow">Happy Birthday Sapna</h1>
    <p>See your wishes by <strong>TUNU</strong></p>
    <button onclick="showWishes()">View Wishes</button>
  </div>

  <div class="container" id="main">
    <h1 class="glow">HAPPY BIRTHDAY SAPNA</h1>
    <p>
      Enjoy your day. God bless you!<br>
      Thank you so much for coming into our lives, friend.<br>
      Today is your birthday, and sadly, I won't be able to celebrate it with you in person due to the distance.<br>
      But I want you to celebrate it joyfully, and I will be praying to God for your happiness.<br><br>
      I pray that all the years ahead bring only good things for you. May all your dreams come true.<br>
      I also pray that your vision for life becomes clear, And may your life always be filled with happiness.<br><br>
      I'm not exactly sure whether you're turning 18 or 19, But whatever the number is, always keep smiling and stay happy.<br>
      A special thank you for being my friend. If you weren’t there, I wouldn't be where I am today.<br>
      I wouldn't have received so much help.<br><br>
      I request you — please never stop supporting me. Because if you step back, I won’t be able to succeed the way I want to.<br>
      Thank you, Sapna. Thank you so much!<br><br>
      And yes — don’t forget to throw a party, okay?
    </p>
  </div>

  <canvas class="confetti" id="confetti-canvas"></canvas>
  <script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.4.0/dist/confetti.browser.min.js"></script>
  <script>
    function showWishes() {
      document.getElementById("intro").style.display = "none";
      document.getElementById("main").style.display = "flex";
    }

    const duration = 15 * 1000;
    const animationEnd = Date.now() + duration;
    const defaults = { startVelocity: 30, spread: 360, ticks: 60, zIndex: 0 };

    function randomInRange(min, max) {
      return Math.random() * (max - min) + min;
    }

    const interval = setInterval(function() {
      const timeLeft = animationEnd - Date.now();

      if (timeLeft <= 0) {
        return clearInterval(interval);
      }

      const particleCount = 50 * (timeLeft / duration);
      confetti(Object.assign({}, defaults, {
        particleCount,
        origin: { x: randomInRange(0.1, 0.3), y: Math.random() - 0.2 }
      }));
      confetti(Object.assign({}, defaults, {
        particleCount,
        origin: { x: randomInRange(0.7, 0.9), y: Math.random() - 0.2 }
      }));
    }, 250);
  </script>
</body>
</html>
