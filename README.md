<p align="center">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 860 220" width="860" height="220">
  <defs>
    <!-- Deep dark bg -->
    <linearGradient id="headerBg" x1="0" y1="0" x2="1" y2="1" gradientUnits="objectBoundingBox">
      <stop offset="0%" stop-color="#0D1117"/>
      <stop offset="100%" stop-color="#111827"/>
    </linearGradient>
    <!-- Accent bar gradient: cyan → purple -->
    <linearGradient id="accentBar" x1="0" y1="0" x2="1" y2="0" gradientUnits="objectBoundingBox">
      <stop offset="0%"   stop-color="#00C8FF"/>
      <stop offset="50%"  stop-color="#7B5FE8"/>
      <stop offset="100%" stop-color="#A855F7"/>
    </linearGradient>
    <!-- Subtle glow under title -->
    <radialGradient id="glow" cx="50%" cy="50%" r="50%">
      <stop offset="0%"   stop-color="#7B5FE8" stop-opacity="0.18"/>
      <stop offset="100%" stop-color="#7B5FE8" stop-opacity="0"/>
    </radialGradient>
    <!-- Dot grid pattern -->
    <pattern id="dots" x="0" y="0" width="28" height="28" patternUnits="userSpaceOnUse">
      <circle cx="1.5" cy="1.5" r="1.2" fill="#ffffff" opacity="0.04"/>
    </pattern>
  </defs>

  <!-- Background -->
  <rect width="860" height="220" fill="url(#headerBg)"/>
  <!-- Dot grid overlay -->
  <rect width="860" height="220" fill="url(#dots)"/>
  <!-- Subtle glow behind text -->
  <ellipse cx="430" cy="108" rx="280" ry="70" fill="url(#glow)"/>

  <!-- Left geometric accent: stacked short lines -->
  <line x1="44" y1="72"  x2="80" y2="72"  stroke="#00C8FF" stroke-width="1.5" opacity="0.5"/>
  <line x1="44" y1="80"  x2="64" y2="80"  stroke="#00C8FF" stroke-width="1"   opacity="0.3"/>
  <line x1="44" y1="88"  x2="72" y2="88"  stroke="#7B5FE8" stroke-width="1"   opacity="0.25"/>

  <!-- Right geometric accent (mirrored) -->
  <line x1="816" y1="72"  x2="780" y2="72"  stroke="#A855F7" stroke-width="1.5" opacity="0.5"/>
  <line x1="816" y1="80"  x2="796" y2="80"  stroke="#A855F7" stroke-width="1"   opacity="0.3"/>
  <line x1="816" y1="88"  x2="788" y2="88"  stroke="#7B5FE8" stroke-width="1"   opacity="0.25"/>

  <!-- Small bracket corners (top-left) -->
  <path d="M32,48 L32,32 L52,32" fill="none" stroke="#00C8FF" stroke-width="1.5" opacity="0.35" stroke-linecap="round"/>
  <!-- Small bracket corners (top-right) -->
  <path d="M828,48 L828,32 L808,32" fill="none" stroke="#A855F7" stroke-width="1.5" opacity="0.35" stroke-linecap="round"/>
  <!-- Small bracket corners (bottom-left) -->
  <path d="M32,172 L32,188 L52,188" fill="none" stroke="#00C8FF" stroke-width="1.5" opacity="0.2" stroke-linecap="round"/>
  <!-- Small bracket corners (bottom-right) -->
  <path d="M828,172 L828,188 L808,188" fill="none" stroke="#A855F7" stroke-width="1.5" opacity="0.2" stroke-linecap="round"/>

  <!-- Eyebrow label -->
  <text x="430" y="70" text-anchor="middle" font-family="'Fira Code', 'Courier New', monospace" font-size="11" fill="#00C8FF" opacity="0.75" letter-spacing="3">FULL-STACK JS / NODE.JS</text>

  <!-- Main title -->
  <text x="430" y="118" text-anchor="middle" font-family="'Segoe UI', 'Arial', sans-serif" font-size="38" font-weight="700" fill="#F0F6FF" letter-spacing="-0.5">Bùi Lê Huy Phước</text>

  <!-- Accent divider line -->
  <rect x="300" y="130" width="260" height="2.5" rx="1.5" fill="url(#accentBar)" opacity="0.85"/>

  <!-- Tech stack tags — inline pill badges -->
  <!-- Node.js -->
  <rect x="154" y="148" width="72" height="22" rx="11" fill="#1a2e1a" stroke="#3FB950" stroke-width="1"/>
  <text x="190" y="163" text-anchor="middle" font-family="'Fira Code', monospace" font-size="11" fill="#3FB950" font-weight="600">Node.js</text>
  <!-- TypeScript -->
  <rect x="236" y="148" width="86" height="22" rx="11" fill="#162032" stroke="#3178C6" stroke-width="1"/>
  <text x="279" y="163" text-anchor="middle" font-family="'Fira Code', monospace" font-size="11" fill="#3178C6" font-weight="600">TypeScript</text>
  <!-- JavaScript -->
  <rect x="332" y="148" width="86" height="22" rx="11" fill="#1f1a00" stroke="#F7DF1E" stroke-width="1"/>
  <text x="375" y="163" text-anchor="middle" font-family="'Fira Code', monospace" font-size="11" fill="#F7DF1E" font-weight="600">JavaScript</text>
  <!-- React -->
  <rect x="428" y="148" width="60" height="22" rx="11" fill="#0d1f2d" stroke="#61DAFB" stroke-width="1"/>
  <text x="458" y="163" text-anchor="middle" font-family="'Fira Code', monospace" font-size="11" fill="#61DAFB" font-weight="600">React</text>
  <!-- Next.js -->
  <rect x="498" y="148" width="68" height="22" rx="11" fill="#1a1a1a" stroke="#e2e2e2" stroke-width="1"/>
  <text x="532" y="163" text-anchor="middle" font-family="'Fira Code', monospace" font-size="11" fill="#e2e2e2" font-weight="600">Next.js</text>
  <!-- REST API -->
  <rect x="576" y="148" width="72" height="22" rx="11" fill="#1e0d2e" stroke="#A855F7" stroke-width="1"/>
  <text x="612" y="163" text-anchor="middle" font-family="'Fira Code', monospace" font-size="11" fill="#A855F7" font-weight="600">REST API</text>

  <!-- Tagline -->
  <text x="430" y="200" text-anchor="middle" font-family="'Segoe UI', Arial, sans-serif" font-size="13" fill="#8892a4" letter-spacing="0.3">Building reliable web services &amp; full-stack JS applications</text>
</svg>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=23521228-BuiLeHuyPhuoc&label=Profile+Views&color=0e75b6&style=for-the-badge" alt="Profile Views" />
  <img src="https://img.shields.io/github/followers/23521228-BuiLeHuyPhuoc?label=Followers&style=for-the-badge&color=blue&labelColor=0D1117" alt="Followers" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=24&duration=3000&pause=1000&color=00C8FF&center=true&vCenter=true&width=750&height=70&lines=Xin+chao%2C+minh+la+Phuoc+%F0%9F%91%8B;Backend+Developer+%E2%9A%99%EF%B8%8F;Node.js+%7C+TypeScript+%7C+REST+API;React+%26+Next.js+%F0%9F%92%BB;Welcome+to+my+GitHub!+%E2%9C%A8" alt="Typing SVG" />
</p>

### 📸 Gallery

<table align="center">
  <tr>
    <td width="33%" align="center" style="padding: 8px;">
      <img src="https://github.com/user-attachments/assets/1dfcd99e-afe7-46db-873e-e9eaeb59fb02" alt="image 1" width="100%" style="border-radius: 12px;" />
    </td>
    <td width="33%" align="center" style="padding: 8px;">
      <img src="https://github.com/user-attachments/assets/8b2c4798-9dd7-47e4-8eb4-b7f0e4705ec4" alt="image 2" width="100%" style="border-radius: 12px;" />
    </td>
    <td width="33%" align="center" style="padding: 8px;">
      <img src="https://github.com/user-attachments/assets/7b5570a1-1d0a-4023-b6d3-f7d0f5836528" alt="image 3" width="100%" style="border-radius: 12px;" />
    </td>
  </tr>
</table>

### 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=23521228-BuiLeHuyPhuoc&show_icons=true&theme=radical&hide_border=true&count_private=true&include_all_commits=true&rank_icon=github" width="380" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=23521228-BuiLeHuyPhuoc&layout=compact&theme=radical&hide_border=true&langs_count=8" width="340" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=23521228-BuiLeHuyPhuoc&theme=radical&hide_border=true&background=0D1117&stroke=7B2FBE&ring=00BFFF&fire=FF4500&currStreakLabel=00BFFF&sideLabels=ffffff" width="720" alt="GitHub Streak" />
</p>

### 🌐 Contribution Activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=23521228-BuiLeHuyPhuoc&custom_title=Contribution%20Graph&bg_color=0D1117&color=00BFFF&line=7B2FBE&point=00BFFF&area=true&area_color=00BFFF&hide_border=true&radius=8" width="720" alt="Contribution Graph" />
</p>

### 🐍 Contribution Snake

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/23521228-BuiLeHuyPhuoc/23521228-BuiLeHuyPhuoc/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/23521228-BuiLeHuyPhuoc/23521228-BuiLeHuyPhuoc/output/github-snake.svg" />
    <img alt="Snake animation" src="https://raw.githubusercontent.com/23521228-BuiLeHuyPhuoc/23521228-BuiLeHuyPhuoc/output/github-snake-dark.svg" width="720" />
  </picture>
</p>

### 🤝 Connect With Me

<p align="center">
  <a href="mailto:23521228@gm.uit.edu.vn">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/23521228-BuiLeHuyPhuoc">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://www.facebook.com/">
    <img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" />
  </a>
</p>

<p align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical" alt="Random Dev Quote" />
</p>

<p align="center">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 860 100" width="860" height="100">
  <defs>
    <linearGradient id="footerAccent" x1="0" y1="0" x2="1" y2="0" gradientUnits="objectBoundingBox">
      <stop offset="0%"   stop-color="#00C8FF"/>
      <stop offset="50%"  stop-color="#7B5FE8"/>
      <stop offset="100%" stop-color="#A855F7"/>
    </linearGradient>
  </defs>

  <!-- Dark background -->
  <rect width="860" height="100" fill="#0D1117"/>

  <!-- Top accent line -->
  <rect x="0" y="0" width="860" height="2" fill="url(#footerAccent)" opacity="0.7"/>

  <!-- Bracket corners top-left -->
  <path d="M20,16 L20,8 L32,8" fill="none" stroke="#00C8FF" stroke-width="1.2" opacity="0.4" stroke-linecap="round"/>
  <!-- Bracket corners top-right -->
  <path d="M840,16 L840,8 L828,8" fill="none" stroke="#A855F7" stroke-width="1.2" opacity="0.4" stroke-linecap="round"/>

  <!-- Main text -->
  <text x="430" y="52" text-anchor="middle" font-family="'Segoe UI', Arial, sans-serif" font-size="18" font-weight="600" fill="#F0F6FF" opacity="0.9">Thanks for visiting!</text>

  <!-- Subtext in monospace -->
  <text x="430" y="74" text-anchor="middle" font-family="'Fira Code', 'Courier New', monospace" font-size="11" fill="#8892a4" letter-spacing="1">// keep coding &amp; keep growing</text>

  <!-- Bottom accent line (lighter) -->
  <rect x="340" y="88" width="180" height="1.5" rx="1" fill="url(#footerAccent)" opacity="0.4"/>
</svg>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=13&pause=2000&color=555555&center=true&vCenter=true&width=520&lines=Made+with+%E2%9D%A4%EF%B8%8F+by+Phuoc+%7C+Keep+coding+and+keep+growing!" alt="footer text" />
</p>
