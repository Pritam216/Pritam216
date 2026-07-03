# 🪐 Hello World, I'm Pritam Kumar Roy! <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExM2NuM2Z6YjZ0ZzR3Ym13N2o4ZXF2MTBrY2Z0ZzR3Ym13N2o4ZSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/WUlNh76f6vA8WMea07/giphy.gif" width="35">

<!-- =================================================================================== -->
<!-- FEATURE 1: CYBERPUNK SVG BANNER & FEATURE 2: ANIMATED TYPING HEADER                -->
<!-- =================================================================================== -->
<div align="center">
  <svg viewBox="0 0 850 260" width="100%" style="background: #0a0a12; font-family: 'Segoe UI', system-ui, sans-serif; border-radius: 12px; border: 2px solid #00f0ff; box-shadow: 0 0 20px rgba(0, 240, 255, 0.2);">
    <!-- Cyberpunk Grid Background -->
    <defs>
      <pattern id="cyber-grid" width="40" height="40" patternUnits="userSpaceOnUse">
        <path d="M 40 0 L 0 0 0 40" fill="none" stroke="#14142b" stroke-width="1"/>
      </pattern>
      <linearGradient id="neon-glow" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#00f0ff" />
        <stop offset="50%" stop-color="#ff007f" />
        <stop offset="100%" stop-color="#7000ff" />
      </linearGradient>
    </defs>
    <rect width="100%" height="100%" fill="#06060e"/>
    <rect width="100%" height="100%" fill="url(#cyber-grid)"/>
    
    <!-- Decorative Tech Accents -->
    <path d="M 10 25 L 300 25 L 320 45 L 840 45" fill="none" stroke="#00f0ff" stroke-width="1" stroke-dasharray="5,5"/>
    <path d="M 10 235 L 530 235 L 550 215 L 840 215" fill="none" stroke="#ff007f" stroke-width="1"/>
    <circle cx="20" cy="25" r="3" fill="#00f0ff"/>
    <circle cx="830" cy="215" r="3" fill="#ff007f"/>

    <!-- Main Title -->
    <text x="50%" y="115" dominant-baseline="middle" text-anchor="middle" font-size="42" font-weight="900" fill="url(#neon-glow)" letter-spacing="6" style="filter: drop-shadow(0px 0px 8px rgba(0,240,255,0.6));">
      PRITAM KUMAR ROY
    </text>

    <!-- Animated Typing Header -->
    <text x="50%" y="170" dominant-baseline="middle" text-anchor="middle" font-size="18" font-weight="600" fill="#00f0ff" letter-spacing="2">
      ENGINEERING INTELLIGENT SYSTEMS
      <animate attributeName="opacity" values="1;0;1" dur="1.5s" repeatCount="indefinite"/>
    </text>
    
    <!-- Code Bracket Accents -->
    <text x="40" y="130" font-size="60" font-weight="100" fill="#1d1d3d">&lt;</text>
    <text x="780" y="130" font-size="60" font-weight="100" fill="#1d1d3d">&gt;</text>
  </svg>
</div>

<br>

<!-- =================================================================================== -->
<!-- FEATURE 3: BENTO-STYLE LAYOUT USING HTML TABLES                                     -->
<!-- FEATURE 4: GLASSMORPHISM-STYLE SVG CARDS (SIMULATED VIA EMBEDDED SVGs)              -->
<!-- =================================================================================== -->
<table width="100%" border="0" cellpadding="10" cellspacing="0" style="border-collapse: collapse;">
  <tr>
    <!-- Left Column: Core Bio / Terminal Area -->
    <td width="55%" valign="top" style="border: none; padding: 6px;">
      <svg viewBox="0 0 450 280" width="100%" style="background: rgba(10, 10, 18, 0.85); border-radius: 10px; border: 1px solid rgba(255, 0, 127, 0.3); box-shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.37);">
        <!-- Glassmorphism Blur & Gradient Background Overlay -->
        <rect width="100%" height="100%" fill="none"/>
        <!-- Top bar representing simulated interface windows -->
        <rect width="100%" height="30" fill="rgba(255, 255, 255, 0.03)" stroke="rgba(255, 0, 127, 0.2)" stroke-width="1"/>
        <circle cx="20" cy="15" r="5" fill="#ff5f56"/>
        <circle cx="38" cy="15" r="5" fill="#ffbd2e"/>
        <circle cx="56" cy="15" r="5" fill="#27c93f"/>
        <text x="430" y="20" text-anchor="end" font-size="11" fill="#666" font-family="monospace">system.profile</text>
        
        <!-- Feature 6: AI Terminal Content -->
        <g font-family="monospace" font-size="13" fill="#e0e0ff">
          <text x="25" y="70" fill="#ff007f">⚡ pritam@core_node:~#</text>
          <text x="205" y="70" fill="#ffffff">cat developer.json</text>
          
          <text x="25" y="100" fill="#00f0ff">{</text>
          <text x="45" y="125" fill="#9efeff">"identity":</text> <text x="165" y="125" fill="#ffb86c">"Computer Science Engineer & Builder",</text>
          <text x="45" y="150" fill="#9efeff">"core_focus":</text> <text x="165" y="150" fill="#ffb86c">"AI/ML Systems & Hardware Hack Sub-layers",</text>
          <text x="45" y="175" fill="#9efeff">"architectures":</text> <text x="185" y="175" fill="#ffb86c">["Multi-Agent Networks", "RAG"],</text>
          <text x="45" y="200" fill="#9efeff">"hardware_stack":</text> <text x="195" y="200" fill="#ffb86c">["ESP32 Microcontrollers", "IoT Core"],</text>
          <text x="45" y="225" fill="#9efeff">"status":</text> <text x="125" y="225" fill="#50fa7b">"Actively compiling next-gen nodes..."</text>
          <text x="25" y="250" fill="#00f0ff">}</text>
          <text x="25" y="270" fill="#50fa7b">▒</text>
        </g>
      </svg>
    </td>
    <!-- Right Column: Quick Stats Mini-Dashboard -->
    <td width="45%" valign="top" style="border: none; padding: 6px;">
      <svg viewBox="0 0 370 280" width="100%" style="background: rgba(10, 10, 18, 0.85); border-radius: 10px; border: 1px solid rgba(0, 240, 255, 0.3); box-shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.37);">
        <rect width="100%" height="30" fill="rgba(255, 255, 255, 0.03)" stroke="rgba(0, 240, 255, 0.2)" stroke-width="1"/>
        <text x="20" y="20" font-size="12" font-weight="bold" fill="#00f0ff" font-family="sans-serif">🛰️ METRICS DASHBOARD</text>
        
        <!-- Live System Node indicators -->
        <g font-family="sans-serif" font-size="13" fill="#ffffff">
          <!-- Node 1 -->
          <rect x="20" y="55" width="330" height="45" rx="6" fill="rgba(255,255,255,0.02)" stroke="rgba(255,255,255,0.05)"/>
          <circle cx="40" cy="77" r="5" fill="#50fa7b"/>
          <text x="60" y="73" font-weight="600">YojnaBot Cluster</text>
          <text x="60" y="90" font-size="11" fill="#888">Status: Functional • Multi-lingual Subsystems Active</text>

          <!-- Node 2 -->
          <rect x="20" y="115" width="330" height="45" rx="6" fill="rgba(255,255,255,0.02)" stroke="rgba(255,255,255,0.05)"/>
          <circle cx="40" cy="137" r="5" fill="#00f0ff"/>
          <text x="60" y="133" font-weight="600">DataMind-2.0 Node</text>
          <text x="60" y="150" font-size="11" fill="#888">Automated Exploratory Analytics Pipeline</text>

          <!-- Node 3 -->
          <rect x="20" y="175" width="330" height="45" rx="6" fill="rgba(255,255,255,0.02)" stroke="rgba(255,255,255,0.05)"/>
          <circle cx="40" cy="197" r="5" fill="#ffb86c"/>
          <text x="60" y="193" font-weight="600">PritamBuilds Tech Hub</text>
          <text x="60" y="210" font-size="11" fill="#888">Hardware Engine: Microcontrollers & Hardware Hack</text>
          
          <!-- Core Target System Bar -->
          <text x="20" y="245" font-size="11" fill="#00f0ff" font-family="monospace">System Core Initialization Integrity:</text>
          <rect x="20" y="255" width="330" height="8" rx="4" fill="#14142b"/>
          <rect x="20" y="255" width="305" height="8" rx="4" fill="url(#neon-glow)"/>
        </g>
      </svg>
    </td>
  </tr>
</table>

<br>

<!-- =================================================================================== -->
<!-- FEATURE 5: SKILL GALAXY (DYNAMIC VECTOR/ICONS MATRIX)                              -->
<!-- =================================================================================== -->
## 🌌 Skill Galaxy
<p align="center">
  <img src="https://skillicons.dev/icons?i=py,java,js,html,css,cpp,mysql,git,github,docker,vercel,linux" alt="Skill Galaxy Phase 1" /><br><br>
  <img src="https://skillicons.dev/icons?i=fastapi,flask,bootstrap,matlab,arduino,raspberrypi,sublime,vscode,idea,postman,scikit-learn,tensorflow" alt="Skill Galaxy Phase 2" />
</p>

<br>

<!-- =================================================================================== -->
<!-- MERMAID DIAGRAM ENGINE INFRASTRUCTURE                                              -->
<!-- Contains Maps, Agent Frameworks, Architecture Arrays and Operational Timelines     -->
<!-- =================================================================================== -->
## 🧠 Architectural Synapses & Systems

### 🗺️ Mermaid AI Brain Mind Map
```mermaid
mindmap
  root((AI Intelligence Matrix))
    Natural Language Engineering
      Large Language Models
      Agentic Workflows
      Retrieval-Augmented Generation
    Computer Vision Architecture
      Image Restoration
      Generative Adversarial Networks
      Deep Feature Realignment
    Hardware Synthetics
      Microcontrollers
      Edge Computing Sensors
      IoT Core Matrices
