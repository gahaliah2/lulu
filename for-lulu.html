<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>For Lulu</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,600;1,500&family=Playfair+Display:ital,wght@0,600;1,500&display=swap" rel="stylesheet">
<style>
  :root {
    --gold: #f2c879;
    --navy1: #10142e;
    --navy2: #050611;
    --paper: #fbf3ee;
    --ink: #2a1418;
    --burgundy: #7a1743;
    --pink2: #ff8fb3;
    box-sizing: border-box;
  }
  * { box-sizing: inherit; }
  html, body { height: 100%; margin: 0; }
  html { scroll-padding-top: env(safe-area-inset-top, 0px); }

  body {
    min-height: 100%;
    background: radial-gradient(ellipse at 75% 12%, #232a52 0%, var(--navy1) 45%, var(--navy2) 100%);
    font-family: 'Cormorant Garamond', Georgia, serif;
    color: var(--paper);
    overflow: hidden;
    display: flex;
    align-items: center;
    justify-content: center;
    padding-top: env(safe-area-inset-top, 0px);
    padding-bottom: env(safe-area-inset-bottom, 0px);
    position: relative;
  }

  .sky { position: absolute; inset: 0; overflow: hidden; }
  .star {
    position: absolute;
    width: 2px; height: 2px;
    background: #fff;
    border-radius: 50%;
    animation: twinkle 3s ease-in-out infinite;
  }
  @keyframes twinkle { 0%, 100% { opacity: 0.25; } 50% { opacity: 1; } }
  .moon {
    position: absolute;
    top: 6%; right: 8%;
    width: 54px; height: 54px;
    border-radius: 50%;
    background: radial-gradient(circle at 35% 35%, #fffef2, #f3e8bd 60%, #e9d89a 100%);
    box-shadow: 0 0 40px 14px rgba(255, 250, 210, 0.35);
  }
  .shooting {
    position: absolute;
    top: 18%; left: 8%;
    width: 90px; height: 2px;
    background: linear-gradient(to left, rgba(255,255,255,0.9), transparent);
    transform: rotate(-18deg);
    opacity: 0;
    animation: shoot 6s ease-in 1.2s infinite;
  }
  @keyframes shoot {
    0% { opacity: 0; transform: translate(0,0) rotate(-18deg); }
    4% { opacity: 1; }
    14% { opacity: 0; transform: translate(160px, 70px) rotate(-18deg); }
    100% { opacity: 0; }
  }

  .scene {
    position: relative;
    width: min(92vw, 460px);
    height: min(92vh, 720px);
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: flex-end;
    padding-bottom: 3vh;
    z-index: 2;
  }

  .title {
    font-family: 'Playfair Display', serif;
    font-style: italic;
    font-size: clamp(1.7rem, 7vw, 2.4rem);
    color: #ffd7e6;
    text-shadow: 0 0 10px rgba(255, 143, 184, 0.85), 0 0 28px rgba(255, 111, 156, 0.5);
    margin-bottom: auto;
    margin-top: 3vh;
    text-align: center;
  }

  /* burst, on opening the card */
  .burst {
    position: absolute;
    inset: 0;
    pointer-events: none;
    overflow: visible;
    z-index: 10;
  }
  .burst-item {
    position: absolute;
    left: 50%;
    top: 38%;
    transform: translate(-50%, -50%);
    opacity: 0;
    animation: burstFly var(--bd, 1.3s) ease-out var(--bdelay, 0s) forwards;
    filter: drop-shadow(0 2px 4px rgba(0,0,0,0.3));
  }
  @keyframes burstFly {
    0%   { transform: translate(-50%, -50%) translate(0, 0) scale(0.3) rotate(0deg); opacity: 0; }
    18%  { opacity: 1; }
    100% { transform: translate(-50%, -50%) translate(var(--bx), var(--by)) scale(1) rotate(var(--br)); opacity: 0; }
  }

  /* envelope */
  .envelope-wrap {
    position: relative;
    z-index: 60;
    width: min(64vw, 240px);
    margin-top: 1.2em;
    cursor: pointer;
    perspective: 900px;
  }
  .envelope-body {
    position: relative;
    width: 100%;
    aspect-ratio: 3 / 2;
    background: linear-gradient(155deg, #ffd0e0, var(--pink2));
    border-radius: 6px;
    box-shadow: 0 16px 36px rgba(0,0,0,0.5);
    overflow: hidden;
  }
  .envelope-body::before {
    content: "";
    position: absolute;
    inset: 0;
    background: linear-gradient(155deg, rgba(255,255,255,0.35), transparent 55%);
  }
  .flap {
    position: absolute;
    inset: 0;
    background: linear-gradient(160deg, #ffe1ec, #ff8fb3);
    clip-path: polygon(0 0, 100% 0, 50% 62%);
    transform-origin: top center;
    transition: transform 0.9s cubic-bezier(.6,-0.2,.3,1.2);
    z-index: 3;
  }
  .heart {
    position: absolute;
    left: 50%; top: 60%;
    transform: translate(-50%, -50%);
    font-size: 1.3rem;
    z-index: 2;
    filter: drop-shadow(0 2px 4px rgba(0,0,0,0.35));
  }
  .tap-label {
    text-align: center;
    font-style: italic;
    opacity: 0.75;
    margin-top: 0.6em;
    font-size: 0.95rem;
    transition: opacity 0.5s ease;
  }

  .scene.open .flap { transform: rotateX(-160deg); }
  .scene.open .tap-label { opacity: 0; }

  .note {
    position: absolute;
    left: 50%;
    bottom: 4%;
    transform: translate(-50%, 0) scale(0.9);
    width: min(84vw, 300px);
    max-height: 62vh;
    overflow-y: auto;
    background: var(--paper);
    color: var(--ink);
    border: 1px solid var(--gold);
    border-radius: 6px;
    padding: 1.3em 1.2em;
    text-align: center;
    opacity: 0;
    box-shadow: 0 24px 50px rgba(0,0,0,0.55);
    transition: opacity 0.8s ease 1s, transform 0.8s ease 1s, bottom 0.8s ease 1s;
    z-index: 4;
  }
  .scene.open .note {
    opacity: 1;
    bottom: 34%;
    transform: translate(-50%, 0) scale(1);
  }
  .note-label {
    font-family: 'Playfair Display', serif;
    font-style: italic;
    color: var(--burgundy);
    font-size: 1.05rem;
    margin-bottom: 0.5em;
  }
  .note-message {
    font-family: 'Playfair Display', serif;
    font-size: clamp(0.95rem, 4.4vw, 1.08rem);
    line-height: 1.5;
  }

  @media (prefers-reduced-motion: reduce) {
    .burst-item, .flap, .note, .star, .shooting { animation: none !important; transition: none !important; }
  }
</style>
</head>
<body>

<div class="sky" id="sky"></div>
<div class="moon"></div>
<div class="shooting"></div>

<div class="scene" id="scene">
  <div class="title">For Lulu</div>

  <div class="envelope-wrap" id="envelope">
    <div class="envelope-body">
      <div class="heart">💗</div>
      <div class="flap" id="flap"></div>
    </div>
    <div class="burst" id="burst"></div>
  </div>
  <div class="tap-label" id="tapLabel">tap the envelope</div>

  <div class="note">
    <div class="note-label">My dear Lulu</div>
    <div class="note-message">
      I am so grateful to have you in my life.<br>May you be in my life—in this world and in Paradise
    </div>
  </div>
</div>

<script>
  const sky = document.getElementById('sky');
  for (let i = 0; i < 60; i++) {
    const s = document.createElement('span');
    s.className = 'star';
    s.style.left = Math.random() * 100 + '%';
    s.style.top = Math.random() * 70 + '%';
    s.style.animationDelay = (Math.random() * 3).toFixed(2) + 's';
    sky.appendChild(s);
  }

  const scene = document.getElementById('scene');
  const envelope = document.getElementById('envelope');
  const burst = document.getElementById('burst');
  const kinds = ['❤️', '💗', '🌹', '💕'];

  function fireBurst() {
    burst.innerHTML = '';
    const count = 18;
    for (let i = 0; i < count; i++) {
      const item = document.createElement('span');
      item.className = 'burst-item';
      item.textContent = kinds[Math.floor(Math.random() * kinds.length)];
      item.style.fontSize = (1.1 + Math.random() * 0.9).toFixed(2) + 'rem';

      const angle = -Math.PI * 0.15 - Math.random() * Math.PI * 0.7; // mostly upward/outward
      const dist = 90 + Math.random() * 170;
      const bx = Math.cos(angle) * dist;
      const by = Math.sin(angle) * dist;

      item.style.setProperty('--bx', bx.toFixed(1) + 'px');
      item.style.setProperty('--by', by.toFixed(1) + 'px');
      item.style.setProperty('--br', (Math.random() * 90 - 45).toFixed(0) + 'deg');
      item.style.setProperty('--bd', (1.1 + Math.random() * 0.5).toFixed(2) + 's');
      item.style.setProperty('--bdelay', (Math.random() * 0.25).toFixed(2) + 's');

      burst.appendChild(item);
    }
  }

  envelope.addEventListener('click', () => {
    const opening = !scene.classList.contains('open');
    scene.classList.toggle('open');
    if (opening) fireBurst();
  });
</script>

</body>
</html>
