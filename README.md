<!-- Header GIF with parallax effect -->
<div align="center">
  <div style="perspective: 1000px;">
    <img src="./anime1.gif" alt="Luffy One Piece" width="100%" style="transform-style: preserve-3d; transform: rotateX(10deg); transition: transform 0.5s ease;" onmouseover="this.style.transform='rotateX(0deg)'" onmouseout="this.style.transform='rotateX(10deg)'"/>
  </div>
</div>

<!-- Animated name with game-like text effects -->
<p align="center">
  <svg width="100%" height="120">
    <defs>
      <linearGradient id="rainbow" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#ff0000" />
        <stop offset="16%" stop-color="#ff7f00" />
        <stop offset="32%" stop-color="#ffff00" />
        <stop offset="48%" stop-color="#00ff00" />
        <stop offset="64%" stop-color="#0000ff" />
        <stop offset="80%" stop-color="#4b0082" />
        <stop offset="100%" stop-color="#9400d3" />
      </linearGradient>
      <filter id="glow" x="-30%" y="-30%" width="160%" height="160%">
        <feGaussianBlur stdDeviation="3" result="blur" />
        <feComposite in="SourceGraphic" in2="blur" operator="over" />
      </filter>
    </defs>
    <text x="50%" y="50%" dominant-baseline="middle" text-anchor="middle" font-size="60" font-family="'Press Start 2P', cursive" fill="url(#rainbow)" filter="url(#glow)">
      <animate attributeName="opacity" values="0.4;1;0.4" dur="3s" repeatCount="indefinite" />
      <animateTransform attributeName="transform" type="scale" values="1;1.05;1" dur="2s" repeatCount="indefinite" />
      Parth4042
    </text>
  </svg>
</p>

<p align="center" style="font-family: 'Press Start 2P', cursive; font-size: 14px; color: #00ff00; text-shadow: 0 0 5px #00ff00;">
  ⚡ LEVEL 99 DEV PIRATE | QUEST: CONQUER THE GRAND LINE OF CODE ⚡
</p>

<!-- Health bar divider -->
<div align="center">
  <div style="height: 4px; width: 80%; background: linear-gradient(90deg, #ff0000 0%, #ffff00 50%, #00ff00 100%); border-radius: 2px; margin: 20px 0; position: relative; overflow: hidden;">
    <div style="position: absolute; top: 0; left: 0; right: 0; bottom: 0; background: repeating-linear-gradient(90deg, rgba(255,255,255,0.1), rgba(255,255,255,0.1) 5px, transparent 5px, transparent 10px); animation: health-pulse 2s infinite;"></div>
  </div>
</div>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap');
  @keyframes health-pulse {
    0% { opacity: 0.3; }
    50% { opacity: 0.7; }
    100% { opacity: 0.3; }
  }
</style>

### 🎮 Player Stats (About Me)

local player = {
  name = "Parth4042",
  class = "Code Pirate Captain",
  level = 99,
  hp = 9999,
  mp = 9999,
  skills = {
    "Bug Slayer", 
    "Stack Overflow Navigator",
    "Coffee Addiction",
    "All-Night Coding"
  },
  current_quest = "Build the One Piece of Web Applications",
  favorite_loot = "Merge Approvals"
}
