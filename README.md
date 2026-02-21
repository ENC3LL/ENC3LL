<div align="center">
  <img src="terminal.svg" width="100%" alt="Terminal UI" />
</div>



<svg width="440" height="110" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <style>
      @keyframes pulse-border {
        0%, 100% { opacity: 0.5; }
        50% { opacity: 1; }
      }
      .pb { animation: pulse-border 3s ease-in-out infinite; }
    </style>
    <linearGradient id="bg-a" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%"   stop-color="#0a0e14"/>
      <stop offset="100%" stop-color="#06090f"/>
    </linearGradient>
    <linearGradient id="redAccent" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%"   stop-color="#c0392b" stop-opacity="1"/>
      <stop offset="100%" stop-color="#c0392b" stop-opacity="0.3"/>
    </linearGradient>
    <filter id="glow-r">
      <feGaussianBlur stdDeviation="2" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <rect width="440" height="110" fill="url(#bg-a)" rx="2"/>

  <!-- left red accent bar -->
  <rect x="0" y="0" width="3" height="110" fill="url(#redAccent)"/>

  <!-- top border line -->
  <rect x="0" y="0" width="440" height="1" fill="#c0392b" opacity="0.4" class="pb"/>

  <!-- bottom border -->
  <rect x="0" y="109" width="440" height="1" fill="#c0392b" opacity="0.15"/>

  <!-- right border faint -->
  <rect x="439" y="0" width="1" height="110" fill="#c0392b" opacity="0.1"/>

  <!-- type label -->
  <text x="18" y="22" font-family="'Courier New', monospace" font-size="9" fill="#3a1a1a" letter-spacing="2">01  //  WEB_APPLICATION</text>

  <!-- name -->
  <text x="18" y="52" font-family="'Courier New', monospace" font-size="22" fill="#c0392b" letter-spacing="4" filter="url(#glow-r)" font-weight="bold">ASAKARO</text>

  <!-- desc -->
  <text x="18" y="72" font-family="'Courier New', monospace" font-size="11" fill="#3a6070">Markdown editor  ·  fast  ·  minimal  ·  no bloat</text>

  <!-- url hint -->
  <text x="18" y="92" font-family="'Courier New', monospace" font-size="10" fill="#2a4555">enc3ll.github.io/asakaro</text>

  <!-- arrow indicator right -->
  <text x="410" y="60" font-family="'Courier New', monospace" font-size="18" fill="#c0392b" opacity="0.4">›</text>

  <!-- status dot -->
  <circle cx="420" cy="22" r="3" fill="#00b4cc" opacity="0.7"/>
  <text x="428" y="26" font-family="'Courier New', monospace" font-size="8" fill="#2a4555">LIVE</text>
</svg>

<svg width="440" height="110" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <style>
      @keyframes pulse-border {
        0%, 100% { opacity: 0.3; }
        50% { opacity: 0.7; }
      }
      .pb { animation: pulse-border 4s ease-in-out infinite; }
    </style>
    <linearGradient id="bg-c" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%"   stop-color="#0a0e14"/>
      <stop offset="100%" stop-color="#060b10"/>
    </linearGradient>
    <linearGradient id="cyanAccent" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%"   stop-color="#00b4cc" stop-opacity="0.8"/>
      <stop offset="100%" stop-color="#00b4cc" stop-opacity="0.2"/>
    </linearGradient>
    <filter id="glow-c">
      <feGaussianBlur stdDeviation="2" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <rect width="440" height="110" fill="url(#bg-c)" rx="2"/>

  <!-- left cyan accent bar -->
  <rect x="0" y="0" width="3" height="110" fill="url(#cyanAccent)"/>

  <!-- top border -->
  <rect x="0" y="0" width="440" height="1" fill="#00b4cc" opacity="0.3" class="pb"/>

  <!-- bottom border -->
  <rect x="0" y="109" width="440" height="1" fill="#00b4cc" opacity="0.1"/>

  <!-- right border faint -->
  <rect x="439" y="0" width="1" height="110" fill="#00b4cc" opacity="0.08"/>

  <!-- type label -->
  <text x="18" y="22" font-family="'Courier New', monospace" font-size="9" fill="#0e2a35" letter-spacing="2">02  //  WEB_APPLICATION</text>

  <!-- name -->
  <text x="18" y="52" font-family="'Courier New', monospace" font-size="22" fill="#00b4cc" letter-spacing="4" filter="url(#glow-c)" font-weight="bold">CLS</text>

  <!-- desc -->
  <text x="18" y="72" font-family="'Courier New', monospace" font-size="11" fill="#3a6070">Card Learning System  ·  spaced repetition  ·  memory</text>

  <!-- url hint -->
  <text x="18" y="92" font-family="'Courier New', monospace" font-size="10" fill="#2a4555">enc3ll.github.io/CLS</text>

  <!-- arrow indicator -->
  <text x="410" y="60" font-family="'Courier New', monospace" font-size="18" fill="#00b4cc" opacity="0.4">›</text>

  <!-- status dot -->
  <circle cx="420" cy="22" r="3" fill="#00b4cc" opacity="0.7"/>
  <text x="428" y="26" font-family="'Courier New', monospace" font-size="8" fill="#2a4555">LIVE</text>
</svg>

<p align="center">
  <a href="https://modrinth.com/user/ENCELL">
    <img src="https://modfolio.creeperkatze.de/modrinth/user/ENCELL" alt="ENCELL Modrinth Stats">
  </a>
</p>
