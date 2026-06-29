<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 300" width="700">
  <defs>
    <style>
      .bg { fill: #0d1117; }
      .lbl { font-family: 'Segoe UI', Arial, sans-serif; font-size: 12px; font-weight: 600; fill: #e6edf3; }
      .ext { font-family: 'Segoe UI', Arial, sans-serif; font-size: 10px; fill: #484f58; }
      .ttl { font-family: 'Segoe UI', Arial, sans-serif; font-size: 19px; font-weight: 700; fill: #e6edf3; }
      .sub { font-family: 'Segoe UI', Arial, sans-serif; font-size: 10px; fill: #484f58; letter-spacing: 2px; }
    </style>
  </defs>

  <!-- Background -->
  <rect width="700" height="300" rx="12" class="bg"/>

  <!-- Top accent bar animated -->
  <rect x="300" y="0" width="0" height="3" rx="1.5" fill="#58a6ff">
    <animate attributeName="x" from="350" to="0" dur="1s" fill="freeze" begin="0.2s"/>
    <animate attributeName="width" from="0" to="700" dur="1s" fill="freeze" begin="0.2s"/>
  </rect>

  <!-- Title fade in -->
  <text x="350" y="38" text-anchor="middle" class="ttl" opacity="0">
    Tech Stack
    <animate attributeName="opacity" from="0" to="1" dur="0.8s" fill="freeze" begin="0.3s"/>
  </text>
  <text x="350" y="54" text-anchor="middle" class="sub" opacity="0">
    LANGUAGES &amp; TOOLS
    <animate attributeName="opacity" from="0" to="1" dur="0.8s" fill="freeze" begin="0.5s"/>
  </text>

  <!-- Accent dots -->
  <circle cx="325" cy="64" r="3" fill="#238636" opacity="0">
    <animate attributeName="opacity" values="0;0;1;0.4;1;0.4;1" dur="2s" repeatCount="indefinite" begin="0.8s"/>
  </circle>
  <circle cx="337" cy="64" r="3" fill="#58a6ff" opacity="0">
    <animate attributeName="opacity" values="0;0;0;1;0.4;1;0.4" dur="2s" repeatCount="indefinite" begin="0.8s"/>
  </circle>
  <circle cx="350" cy="64" r="3" fill="#a371f7" opacity="0">
    <animate attributeName="opacity" values="0;0;0;0;1;0.4;1" dur="2s" repeatCount="indefinite" begin="0.8s"/>
  </circle>
  <circle cx="363" cy="64" r="3" fill="#f78166" opacity="0">
    <animate attributeName="opacity" values="0;0;0;0;0;1;0.4" dur="2s" repeatCount="indefinite" begin="0.8s"/>
  </circle>
  <circle cx="375" cy="64" r="3" fill="#ffa657" opacity="0">
    <animate attributeName="opacity" values="0;0;0;0;0;0;1" dur="2s" repeatCount="indefinite" begin="0.8s"/>
  </circle>

  <!-- ═══════════════ ROW 1 ═══════════════ -->

  <!-- PYTHON card -->
  <g opacity="0">
    <animate attributeName="opacity" from="0" to="1" dur="0.4s" fill="freeze" begin="0.3s"/>
    <animateTransform attributeName="transform" type="translate" from="0,15" to="0,0" dur="0.4s" fill="freeze" begin="0.3s"/>
    <rect x="20" y="80" width="90" height="95" rx="10" fill="#1a2a3a"/>
    <!-- Python logo SVG path -->
    <g transform="translate(42, 95)">
      <!-- top snake (blue) -->
      <path d="M23 0 C14 0 9 3.5 9 8 L9 13 L23 13 L23 15 L5 15 C1 15 -2 18 -2 23 C-2 28 1 31 5 31 L9 31 L9 27 C9 22 12 20 16 20 L24 20 C28 20 31 17 31 13 L31 8 C31 3.5 28 0 23 0 Z" fill="#4da6e0"/>
      <circle cx="15" cy="7.5" r="2.2" fill="white"/>
      <!-- bottom snake (yellow) -->
      <path d="M23 46 C32 46 37 42.5 37 38 L37 33 L23 33 L23 31 L41 31 C45 31 48 28 48 23 C48 18 45 15 41 15 L37 15 L37 19 C37 24 34 26 30 26 L22 26 C18 26 15 29 15 33 L15 38 C15 42.5 18 46 23 46 Z" fill="#ffd43b"/>
      <circle cx="31" cy="38.5" r="2.2" fill="#4da6e0"/>
    </g>
    <text x="65" y="191" text-anchor="middle" class="lbl">Python</text>
    <text x="65" y="203" text-anchor="middle" class="ext">.py</text>
    <!-- float animation -->
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,-6; 0,0" dur="3s" repeatCount="indefinite" begin="1.5s" additive="sum"/>
  </g>

  <!-- C++ card -->
  <g opacity="0">
    <animate attributeName="opacity" from="0" to="1" dur="0.4s" fill="freeze" begin="0.45s"/>
    <animateTransform attributeName="transform" type="translate" from="0,15" to="0,0" dur="0.4s" fill="freeze" begin="0.45s"/>
    <rect x="127" y="80" width="90" height="95" rx="10" fill="#1e2438"/>
    <!-- C++ official logo style -->
    <g transform="translate(150, 98)">
      <!-- Hexagon shape -->
      <polygon points="22,0 38,9 38,27 22,36 6,27 6,9" fill="none" stroke="#659bd3" stroke-width="2.5"/>
      <!-- C letter -->
      <path d="M25 11 C22 11 17 14 17 18 C17 22 22 25 25 25 C27 25 29 24 30 23" fill="none" stroke="#659bd3" stroke-width="2.5" stroke-linecap="round"/>
      <!-- + + -->
      <line x1="32" y1="15" x2="38" y2="15" stroke="#659bd3" stroke-width="2.2" stroke-linecap="round"/>
      <line x1="35" y1="12" x2="35" y2="18" stroke="#659bd3" stroke-width="2.2" stroke-linecap="round"/>
      <line x1="40" y1="15" x2="46" y2="15" stroke="#659bd3" stroke-width="2.2" stroke-linecap="round"/>
      <line x1="43" y1="12" x2="43" y2="18" stroke="#659bd3" stroke-width="2.2" stroke-linecap="round"/>
    </g>
    <text x="172" y="191" text-anchor="middle" class="lbl">C++</text>
    <text x="172" y="203" text-anchor="middle" class="ext">.cpp</text>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,-6; 0,0" dur="3.2s" repeatCount="indefinite" begin="1.8s" additive="sum"/>
  </g>

  <!-- JavaScript card -->
  <g opacity="0">
    <animate attributeName="opacity" from="0" to="1" dur="0.4s" fill="freeze" begin="0.6s"/>
    <animateTransform attributeName="transform" type="translate" from="0,15" to="0,0" dur="0.4s" fill="freeze" begin="0.6s"/>
    <rect x="234" y="80" width="90" height="95" rx="10" fill="#262200"/>
    <!-- JS official square logo -->
    <g transform="translate(255, 97)">
      <rect x="0" y="0" width="44" height="44" rx="3" fill="#f7df1e"/>
      <!-- J letter -->
      <path d="M26 8 L26 30 C26 35 24 37 20 37 C17 37 15 35 14 33" fill="none" stroke="#1a1a00" stroke-width="3.5" stroke-linecap="round" stroke-linejoin="round"/>
      <!-- S letter -->
      <path d="M32 33 C30 36 27 37 24.5 37 C21 37 18 35 18 32 C18 29 20 28 23 27 L25 26 C27.5 25 29 24 29 21.5 C29 19 27 17.5 24.5 17.5 C22 17.5 20.5 19 19.5 21" fill="none" stroke="#1a1a00" stroke-width="3.5" stroke-linecap="round" stroke-linejoin="round"/>
    </g>
    <text x="279" y="191" text-anchor="middle" class="lbl">JavaScript</text>
    <text x="279" y="203" text-anchor="middle" class="ext">.js</text>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,-6; 0,0" dur="3.1s" repeatCount="indefinite" begin="2.1s" additive="sum"/>
  </g>

  <!-- TypeScript card -->
  <g opacity="0">
    <animate attributeName="opacity" from="0" to="1" dur="0.4s" fill="freeze" begin="0.75s"/>
    <animateTransform attributeName="transform" type="translate" from="0,15" to="0,0" dur="0.4s" fill="freeze" begin="0.75s"/>
    <rect x="341" y="80" width="90" height="95" rx="10" fill="#162240"/>
    <!-- TS official square logo -->
    <g transform="translate(362, 97)">
      <rect x="0" y="0" width="44" height="44" rx="3" fill="#3178c6"/>
      <!-- T bar -->
      <line x1="4" y1="13" x2="24" y2="13" stroke="white" stroke-width="4" stroke-linecap="round"/>
      <!-- T stem -->
      <line x1="14" y1="13" x2="14" y2="37" stroke="white" stroke-width="4" stroke-linecap="round"/>
      <!-- S letter -->
      <path d="M30 34 C28 37 25.5 38 23.5 38 C20.5 38 18 36 18 33 C18 30 19.5 29 22.5 28 L24 27.2 C26 26.3 27.5 25.5 27.5 23.5 C27.5 21.5 26 20 23.5 20 C21.5 20 20 21 19 23" fill="none" stroke="white" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"/>
    </g>
    <text x="386" y="191" text-anchor="middle" class="lbl">TypeScript</text>
    <text x="386" y="203" text-anchor="middle" class="ext">.ts</text>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,-6; 0,0" dur="3.3s" repeatCount="indefinite" begin="2.4s" additive="sum"/>
  </g>

  <!-- ═══════════════ ROW 2 ═══════════════ -->

  <!-- RUST card -->
  <g opacity="0">
    <animate attributeName="opacity" from="0" to="1" dur="0.4s" fill="freeze" begin="0.9s"/>
    <animateTransform attributeName="transform" type="translate" from="0,15" to="0,0" dur="0.4s" fill="freeze" begin="0.9s"/>
    <rect x="20" y="193" width="90" height="95" rx="10" fill="#2c1a14"/>
    <!-- Rust gear logo -->
    <g transform="translate(43, 210)">
      <!-- Outer gear ring -->
      <circle cx="22" cy="22" r="18" fill="none" stroke="#f74c00" stroke-width="2.5"/>
      <!-- Gear teeth -->
      <rect x="19" y="1"  width="6" height="5" rx="1.5" fill="#f74c00"/>
      <rect x="19" y="38" width="6" height="5" rx="1.5" fill="#f74c00"/>
      <rect x="1"  y="19" width="5" height="6" rx="1.5" fill="#f74c00"/>
      <rect x="38" y="19" width="5" height="6" rx="1.5" fill="#f74c00"/>
      <!-- diagonal teeth -->
      <rect x="5"  y="5"  width="5" height="5" rx="1" fill="#f74c00" transform="rotate(45 7.5 7.5)"/>
      <rect x="34" y="5"  width="5" height="5" rx="1" fill="#f74c00" transform="rotate(45 36.5 7.5)"/>
      <rect x="5"  y="34" width="5" height="5" rx="1" fill="#f74c00" transform="rotate(45 7.5 36.5)"/>
      <rect x="34" y="34" width="5" height="5" rx="1" fill="#f74c00" transform="rotate(45 36.5 36.5)"/>
      <!-- Inner circle -->
      <circle cx="22" cy="22" r="9" fill="#f74c00"/>
      <circle cx="22" cy="22" r="5" fill="#2c1a14"/>
      <!-- Rust R letter hint -->
      <circle cx="22" cy="22" r="3" fill="none" stroke="#f74c00" stroke-width="1.5"/>
    </g>
    <text x="65" y="304" text-anchor="middle" class="lbl">Rust</text>
    <text x="65" y="316" text-anchor="middle" class="ext">.rs</text>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,-6; 0,0" dur="3.4s" repeatCount="indefinite" begin="2.7s" additive="sum"/>
  </g>

  <!-- GO card -->
  <g opacity="0">
    <animate attributeName="opacity" from="0" to="1" dur="0.4s" fill="freeze" begin="1.05s"/>
    <animateTransform attributeName="transform" type="translate" from="0,15" to="0,0" dur="0.4s" fill="freeze" begin="1.05s"/>
    <rect x="127" y="193" width="90" height="95" rx="10" fill="#0a2030"/>
    <!-- Go gopher simplified face -->
    <g transform="translate(150, 208)">
      <!-- Body/head -->
      <ellipse cx="22" cy="26" rx="18" ry="16" fill="#00acd7"/>
      <!-- Ears -->
      <ellipse cx="5"  cy="20" rx="5" ry="6" fill="#00acd7"/>
      <ellipse cx="39" cy="20" rx="5" ry="6" fill="#00acd7"/>
      <ellipse cx="5"  cy="20" rx="2.5" ry="3.5" fill="#5dcfeb"/>
      <ellipse cx="39" cy="20" rx="2.5" ry="3.5" fill="#5dcfeb"/>
      <!-- Eyes -->
      <circle cx="15" cy="20" r="5" fill="white"/>
      <circle cx="29" cy="20" r="5" fill="white"/>
      <circle cx="16" cy="20" r="2.5" fill="#1a1a1a"/>
      <circle cx="30" cy="20" r="2.5" fill="#1a1a1a"/>
      <circle cx="16.8" cy="19" r="1" fill="white"/>
      <circle cx="30.8" cy="19" r="1" fill="white"/>
      <!-- Nose -->
      <ellipse cx="22" cy="27" rx="5" ry="3" fill="#5dcfeb"/>
      <circle cx="20" cy="27" r="1.2" fill="#1a1a1a"/>
      <circle cx="24" cy="27" r="1.2" fill="#1a1a1a"/>
      <!-- Tooth -->
      <rect x="20" y="30" width="4" height="4" rx="1" fill="white"/>
    </g>
    <text x="172" y="304" text-anchor="middle" class="lbl">Go</text>
    <text x="172" y="316" text-anchor="middle" class="ext">.go</text>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,-6; 0,0" dur="3.2s" repeatCount="indefinite" begin="3s" additive="sum"/>
  </g>

  <!-- KOTLIN card -->
  <g opacity="0">
    <animate attributeName="opacity" from="0" to="1" dur="0.4s" fill="freeze" begin="1.2s"/>
    <animateTransform attributeName="transform" type="translate" from="0,15" to="0,0" dur="0.4s" fill="freeze" begin="1.2s"/>
    <rect x="234" y="193" width="90" height="95" rx="10" fill="#1e1440"/>
    <!-- Kotlin official K logo -->
    <g transform="translate(258, 210)">
      <defs>
        <linearGradient id="kg" x1="0%" y1="0%" x2="100%" y2="100%">
          <stop offset="0%" stop-color="#e44857"/>
          <stop offset="46%" stop-color="#c711e1"/>
          <stop offset="100%" stop-color="#7f52ff"/>
        </linearGradient>
      </defs>
      <!-- K shape using official design: two triangles -->
      <polygon points="0,0 22,0 44,22 22,22" fill="url(#kg)"/>
      <polygon points="0,0 22,22 0,44" fill="url(#kg)" opacity="0.85"/>
      <polygon points="22,22 44,22 44,44 0,44" fill="url(#kg)" opacity="0.7"/>
    </g>
    <text x="279" y="304" text-anchor="middle" class="lbl">Kotlin</text>
    <text x="279" y="316" text-anchor="middle" class="ext">.kt</text>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,-6; 0,0" dur="3.5s" repeatCount="indefinite" begin="3.3s" additive="sum"/>
  </g>

  <!-- DART card -->
  <g opacity="0">
    <animate attributeName="opacity" from="0" to="1" dur="0.4s" fill="freeze" begin="1.35s"/>
    <animateTransform attributeName="transform" type="translate" from="0,15" to="0,0" dur="0.4s" fill="freeze" begin="1.35s"/>
    <rect x="341" y="193" width="90" height="95" rx="10" fill="#0a1e30"/>
    <!-- Dart official logo -->
    <g transform="translate(364, 210)">
      <defs>
        <linearGradient id="dg" x1="0%" y1="0%" x2="100%" y2="100%">
          <stop offset="0%" stop-color="#40c4ff"/>
          <stop offset="100%" stop-color="#0175c2"/>
        </linearGradient>
      </defs>
      <!-- Main dart shape -->
      <path d="M3 3 L16 0 L44 14 L44 30 L30 44 L14 44 L0 30 L0 16 Z" fill="url(#dg)"/>
      <!-- Corner cuts -->
      <path d="M0 16 L3 3 L16 0" fill="#0050a0" opacity="0.6"/>
      <path d="M44 30 L44 14 L50 22 Z" fill="#0050a0" opacity="0.4"/>
      <!-- Center emblem -->
      <circle cx="22" cy="22" r="8" fill="white" opacity="0.9"/>
      <circle cx="22" cy="22" r="5" fill="url(#dg)"/>
      <circle cx="22" cy="22" r="2.5" fill="white"/>
    </g>
    <text x="386" y="304" text-anchor="middle" class="lbl">Dart</text>
    <text x="386" y="316" text-anchor="middle" class="ext">.dart</text>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,-6; 0,0" dur="3.6s" repeatCount="indefinite" begin="3.6s" additive="sum"/>
  </g>

  <!-- Bottom bar -->
  <rect x="0" y="297" width="700" height="3" rx="1.5" fill="url(#bar2)">
    <animate attributeName="opacity" from="0" to="0.8" dur="1s" fill="freeze" begin="1.5s"/>
  </rect>
  <defs>
    <linearGradient id="bar2" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#a371f7"/>
      <stop offset="50%" stop-color="#58a6ff"/>
      <stop offset="100%" stop-color="#238636"/>
    </linearGradient>
  </defs>

</svg>
