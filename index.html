<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For You 🌸</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,600;1,500&family=Playfair+Display:ital@1&family=Dancing+Script:wght@500;700&display=swap" rel="stylesheet">
<style>
  :root{
    --blush:#fbe4ea;
    --petal-deep:#e8829f;
    --petal-mid:#f2a8bd;
    --petal-light:#f9cddb;
    --leaf:#7fa38a;
    --leaf-deep:#5c7f68;
    --paper:#fff8f5;
    --ink:#5a3a45;
    --gold:#c9a15a;
  }
  *{box-sizing:border-box;}
  html,body{
    margin:0; padding:0; min-height:100vh;
    background: radial-gradient(ellipse at 50% -10%, #fff3f6 0%, var(--blush) 55%, #f6d3de 100%);
    font-family: 'Cormorant Garamond', serif;
    color: var(--ink);
    overflow-x:hidden;
  }
  .stage{
    min-height:100vh;
    display:flex; flex-direction:column; align-items:center; justify-content:center;
    padding: 40px 20px 60px;
    position:relative;
  }
  .petal-float{
    position:fixed; top:-40px; pointer-events:none; z-index:0;
    opacity:0.85; animation: fall linear infinite;
  }
  @keyframes fall{
    to { transform: translateY(110vh) rotate(360deg); }
  }
  @media (prefers-reduced-motion: reduce){
    .petal-float{ animation: none; display:none; }
  }

  h1.title{
    font-family:'Dancing Script', cursive;
    font-weight:700;
    font-size: clamp(2.2rem, 6vw, 3.6rem);
    color: var(--petal-deep);
    margin: 0 0 6px;
    text-align:center;
    text-shadow: 0 1px 0 rgba(255,255,255,0.6);
    z-index:2;
  }
  p.subtitle{
    font-style: italic;
    font-size: 1.1rem;
    color: var(--ink);
    opacity:0.75;
    margin: 0 0 34px;
    letter-spacing: 0.03em;
    z-index:2;
  }

  .bouquet-wrap{
    position:relative;
    z-index:2;
    cursor:pointer;
    transition: transform 0.4s ease;
  }
  .bouquet-wrap:hover{ transform: translateY(-4px); }
  .bouquet-wrap svg{
    width: min(78vw, 420px);
    height: auto;
    display:block;
    filter: drop-shadow(0 18px 30px rgba(150, 70, 100, 0.25));
  }

  .hint{
    margin-top: 18px;
    font-size: 0.95rem;
    color: var(--petal-deep);
    opacity:0.7;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    font-family: 'Cormorant Garamond', serif;
    z-index:2;
    animation: pulse 2.2s ease-in-out infinite;
  }
  @keyframes pulse{
    0%,100%{ opacity:0.45; }
    50%{ opacity:0.9; }
  }

  .overlay{
    position:fixed; inset:0;
    background: rgba(90, 58, 69, 0.35);
    backdrop-filter: blur(4px);
    display:flex; align-items:center; justify-content:center;
    opacity:0; pointer-events:none;
    transition: opacity 0.5s ease;
    z-index: 10;
    padding: 20px;
  }
  .overlay.show{ opacity:1; pointer-events:auto; }

  .card{
    background: var(--paper);
    border-radius: 18px;
    max-width: 480px;
    width:100%;
    padding: 44px 38px 36px;
    text-align:center;
    position:relative;
    box-shadow: 0 30px 60px rgba(90,40,60,0.35);
    border: 1px solid rgba(201,161,90,0.35);
    transform: scale(0.85) translateY(20px);
    transition: transform 0.5s cubic-bezier(.2,.8,.3,1.2);
  }
  .overlay.show .card{ transform: scale(1) translateY(0); }

  .card::before{
    content:"";
    position:absolute; inset:10px;
    border: 1px solid rgba(201,161,90,0.4);
    border-radius: 12px;
    pointer-events:none;
  }
  .card .close{
    position:absolute; top:14px; right:16px;
    background:none; border:none;
    font-size: 1.4rem;
    color: var(--petal-deep);
    cursor:pointer;
    line-height:1;
    opacity:0.6;
  }
  .card .close:hover{ opacity:1; }

  .card .flower-emoji{ font-size: 1.6rem; margin-bottom:6px; }

  .card h2{
    font-family:'Dancing Script', cursive;
    font-size: 2.1rem;
    color: var(--petal-deep);
    margin: 4px 0 18px;
  }
  .card .message{
    font-size: 1.15rem;
    line-height: 1.65;
    color: var(--ink);
    margin-bottom: 22px;
  }
  .card .signoff{
    font-style: italic;
    font-size: 1rem;
    color: var(--ink);
    opacity: 0.75;
  }

  footer{
    margin-top: 40px;
    font-size: 0.8rem;
    color: var(--ink);
    opacity: 0.45;
    z-index:2;
    text-align:center;
  }
</style>
</head>
<body>

<div class="stage">
  <h1 class="title">A Little Something For You</h1>
  <p class="subtitle">tap the bouquet, lovelove</p>

  <div class="bouquet-wrap" id="bouquetBtn" role="button" tabindex="0" aria-label="Open your bouquet">
    <svg viewBox="0 0 400 460" xmlns="http://www.w3.org/2000/svg">
      <defs>
        <radialGradient id="petalDeep" cx="35%" cy="30%" r="75%">
          <stop offset="0%" stop-color="#f6b9cb"/>
          <stop offset="100%" stop-color="#e8829f"/>
        </radialGradient>
        <radialGradient id="petalMid" cx="35%" cy="30%" r="75%">
          <stop offset="0%" stop-color="#fbd3df"/>
          <stop offset="100%" stop-color="#f2a8bd"/>
        </radialGradient>
        <radialGradient id="petalLight" cx="35%" cy="30%" r="75%">
          <stop offset="0%" stop-color="#fff0f4"/>
          <stop offset="100%" stop-color="#f9cddb"/>
        </radialGradient>
        <linearGradient id="leafGrad" x1="0%" y1="0%" x2="100%" y2="100%">
          <stop offset="0%" stop-color="#8fb89c"/>
          <stop offset="100%" stop-color="#5c7f68"/>
        </linearGradient>
        <linearGradient id="wrapGrad" x1="0%" y1="0%" x2="0%" y2="100%">
          <stop offset="0%" stop-color="#fff8f5"/>
          <stop offset="100%" stop-color="#f2d9cf"/>
        </linearGradient>
      </defs>

      <path d="M120 300 L200 460 L280 300 Z" fill="url(#wrapGrad)" stroke="#e8c7b8" stroke-width="2"/>
      <path d="M90 290 L200 460 L310 290 L280 260 L200 320 L120 260 Z" fill="#fef1ec" stroke="#e8c7b8" stroke-width="1.5" opacity="0.9"/>

      <path d="M150 300 Q200 330 250 300" stroke="var(--gold)" stroke-width="5" fill="none" stroke-linecap="round"/>
      <path d="M160 302 L145 322 L165 316 Z" fill="var(--gold)"/>
      <path d="M240 302 L255 322 L235 316 Z" fill="var(--gold)"/>

      <path d="M200 300 Q195 220 175 150" stroke="url(#leafGrad)" stroke-width="4" fill="none"/>
      <path d="M200 300 Q205 210 215 130" stroke="url(#leafGrad)" stroke-width="4" fill="none"/>
      <path d="M200 300 Q198 230 200 170" stroke="url(#leafGrad)" stroke-width="4" fill="none"/>
      <path d="M200 300 Q170 240 130 190" stroke="url(#leafGrad)" stroke-width="4" fill="none"/>
      <path d="M200 300 Q230 240 270 190" stroke="url(#leafGrad)" stroke-width="4" fill="none"/>

      <path d="M185 230 Q160 220 155 195 Q185 205 185 230 Z" fill="url(#leafGrad)"/>
      <path d="M215 220 Q245 210 252 185 Q220 195 215 220 Z" fill="url(#leafGrad)"/>
      <path d="M200 260 Q175 255 165 235 Q195 240 200 260 Z" fill="url(#leafGrad)"/>

      <g transform="translate(130,185)">
        <circle r="30" fill="url(#petalLight)"/>
        <g>
          <ellipse cx="0" cy="-16" rx="13" ry="18" fill="url(#petalMid)" transform="rotate(0)"/>
          <ellipse cx="0" cy="-16" rx="13" ry="18" fill="url(#petalMid)" transform="rotate(60)"/>
          <ellipse cx="0" cy="-16" rx="13" ry="18" fill="url(#petalMid)" transform="rotate(120)"/>
          <ellipse cx="0" cy="-16" rx="13" ry="18" fill="url(#petalMid)" transform="rotate(180)"/>
          <ellipse cx="0" cy="-16" rx="13" ry="18" fill="url(#petalMid)" transform="rotate(240)"/>
          <ellipse cx="0" cy="-16" rx="13" ry="18" fill="url(#petalMid)" transform="rotate(300)"/>
        </g>
        <circle r="14" fill="url(#petalDeep)"/>
        <circle r="5" fill="#c9678a"/>
      </g>

      <g transform="translate(270,185)">
        <circle r="30" fill="url(#petalLight)"/>
        <g>
          <ellipse cx="0" cy="-16" rx="13" ry="18" fill="url(#petalMid)" transform="rotate(20)"/>
          <ellipse cx="0" cy="-16" rx="13" ry="18" fill="url(#petalMid)" transform="rotate(80)"/>
          <ellipse cx="0" cy="-16" rx="13" ry="18" fill="url(#petalMid)" transform="rotate(140)"/>
          <ellipse cx="0" cy="-16" rx="13" ry="18" fill="url(#petalMid)" transform="rotate(200)"/>
          <ellipse cx="0" cy="-16" rx="13" ry="18" fill="url(#petalMid)" transform="rotate(260)"/>
          <ellipse cx="0" cy="-16" rx="13" ry="18" fill="url(#petalMid)" transform="rotate(320)"/>
        </g>
        <circle r="14" fill="url(#petalDeep)"/>
        <circle r="5" fill="#c9678a"/>
      </g>

      <g transform="translate(200,150)">
        <circle r="42" fill="url(#petalLight)"/>
        <g>
          <ellipse cx="0" cy="-22" rx="17" ry="24" fill="url(#petalMid)" transform="rotate(0)"/>
          <ellipse cx="0" cy="-22" rx="17" ry="24" fill="url(#petalMid)" transform="rotate(45)"/>
          <ellipse cx="0" cy="-22" rx="17" ry="24" fill="url(#petalMid)" transform="rotate(90)"/>
          <ellipse cx="0" cy="-22" rx="17" ry="24" fill="url(#petalMid)" transform="rotate(135)"/>
          <ellipse cx="0" cy="-22" rx="17" ry="24" fill="url(#petalMid)" transform="rotate(180)"/>
          <ellipse cx="0" cy="-22" rx="17" ry="24" fill="url(#petalMid)" transform="rotate(225)"/>
          <ellipse cx="0" cy="-22" rx="17" ry="24" fill="url(#petalMid)" transform="rotate(270)"/>
          <ellipse cx="0" cy="-22" rx="17" ry="24" fill="url(#petalMid)" transform="rotate(315)"/>
        </g>
        <g>
          <ellipse cx="0" cy="-12" rx="11" ry="15" fill="url(#petalDeep)" transform="rotate(20)"/>
          <ellipse cx="0" cy="-12" rx="11" ry="15" fill="url(#petalDeep)" transform="rotate(90)"/>
          <ellipse cx="0" cy="-12" rx="11" ry="15" fill="url(#petalDeep)" transform="rotate(160)"/>
          <ellipse cx="0" cy="-12" rx="11" ry="15" fill="url(#petalDeep)" transform="rotate(230)"/>
          <ellipse cx="0" cy="-12" rx="11" ry="15" fill="url(#petalDeep)" transform="rotate(300)"/>
        </g>
        <circle r="9" fill="#d1728f"/>
      </g>

      <g transform="translate(160,110)">
        <circle cx="0" cy="-8" r="6" fill="url(#petalLight)"/>
        <circle cx="7" cy="0" r="6" fill="url(#petalLight)"/>
        <circle cx="-7" cy="0" r="6" fill="url(#petalLight)"/>
        <circle cx="4" cy="7" r="6" fill="url(#petalLight)"/>
        <circle cx="-4" cy="7" r="6" fill="url(#petalLight)"/>
        <circle r="4" fill="var(--gold)"/>
      </g>
      <g transform="translate(245,105)">
        <circle cx="0" cy="-8" r="6" fill="url(#petalLight)"/>
        <circle cx="7" cy="0" r="6" fill="url(#petalLight)"/>
        <circle cx="-7" cy="0" r="6" fill="url(#petalLight)"/>
        <circle cx="4" cy="7" r="6" fill="url(#petalLight)"/>
        <circle cx="-4" cy="7" r="6" fill="url(#petalLight)"/>
        <circle r="4" fill="var(--gold)"/>
      </g>
      <g transform="translate(200,90)">
        <circle cx="0" cy="-7" r="5" fill="url(#petalDeep)"/>
        <circle cx="6" cy="1" r="5" fill="url(#petalDeep)"/>
        <circle cx="-6" cy="1" r="5" fill="url(#petalDeep)"/>
        <circle cx="3" cy="6" r="5" fill="url(#petalDeep)"/>
        <circle cx="-3" cy="6" r="5" fill="url(#petalDeep)"/>
        <circle r="3.5" fill="#fff7ec"/>
      </g>

    </svg>
  </div>

  <div class="hint" id="hintText">tap to open</div>

  <footer>made with love, just for you 🤍</footer>
</div>

<div class="overlay" id="overlay">
  <div class="card">
    <button class="close" id="closeBtn" aria-label="Close">✕</button>
    <div class="flower-emoji">🌸</div>
    <h2>To My Lovelove</h2>
    <div class="message">
      Hey lovelove, I just wanted to check in on you. I know today wasn't easy and you were really tired,
      so I hope you're sleeping deeply right now and getting the rest you need.
      <br><br>
      I've been thinking a lot about everything, about us, about the ways I hurt you and the things I should've
      done differently. I'm sorry, genuinely, for all of it. You didn't deserve the hard moments I caused.
      <br><br>
      I'm not saying this to pressure you into anything, I just needed you to know it's real and it's been on my mind.
      For tonight though, just rest. Let today go. I hope you wake up feeling lighter.
      <br><br>
      Sleep well 🤍
    </div>
    <div class="signoff">— your lovelove</div>
  </div>
</div>

<script>
  const colors = ['#f2a8bd', '#f9cddb', '#e8829f'];
  const stage = document.body;
  for (let i = 0; i < 14; i++) {
    const p = document.createElement('div');
    p.className = 'petal-float';
    const size = 8 + Math.random() * 10;
    p.style.left = Math.random() * 100 + 'vw';
    p.style.width = size + 'px';
    p.style.height = size * 1.2 + 'px';
    p.style.background = colors[Math.floor(Math.random() * colors.length)];
    p.style.borderRadius = '60% 40% 60% 40%';
    p.style.animationDuration = (10 + Math.random() * 10) + 's';
    p.style.animationDelay = (Math.random() * 10) + 's';
    stage.appendChild(p);
  }

  const bouquetBtn = document.getElementById('bouquetBtn');
  const overlay = document.getElementById('overlay');
  const closeBtn = document.getElementById('closeBtn');
  const hint = document.getElementById('hintText');

  function openCard(){
    overlay.classList.add('show');
    hint.style.display = 'none';
  }
  function closeCard(){
    overlay.classList.remove('show');
  }

  bouquetBtn.addEventListener('click', openCard);
  bouquetBtn.addEventListener('keypress', (e) => {
    if (e.key === 'Enter' || e.key === ' ') openCard();
  });
  closeBtn.addEventListener('click', closeCard);
  overlay.addEventListener('click', (e) => {
    if (e.target === overlay) closeCard();
  });
</script>

</body>
</html>
