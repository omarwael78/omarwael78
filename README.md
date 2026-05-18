<div>
  <!-- SVG Banner Dynamic Cyberpunk Style -->
  <svg width="100%" height="400" viewBox="0 0 800 400" preserveAspectRatio="xMidYMid meet" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" style="stop-color:#0a0a0a;stop-opacity:1" />
        <stop offset="100%" style="stop-color:#1a1a2e;stop-opacity:1" />
      </linearGradient>
      
      <linearGradient id="glowGreen" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" style="stop-color:#00ff88;stop-opacity:0.3" />
        <stop offset="50%" style="stop-color:#00ff88;stop-opacity:1" />
        <stop offset="100%" style="stop-color:#00ff88;stop-opacity:0.3" />
      </linearGradient>
      
      <filter id="glow">
        <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
        <feMerge>
          <feMergeNode in="coloredBlur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
      
      <style>
        .title {
          font-family: 'Courier New', monospace;
          font-size: 44px;
          font-weight: bold;
          fill: #ffffff;
          letter-spacing: 3px;
        }
        
        .subtitle {
          font-family: 'Courier New', monospace;
          font-size: 18px;
          fill: #00ff88;
        }
        
        .terminal-text {
          font-family: 'Courier New', monospace;
          font-size: 14px;
          fill: #00ff88;
        }
        
        .output-text {
          font-family: 'Courier New', monospace;
          font-size: 14px;
          fill: #ffffff;
        }
        
        .blink {
          animation: blink 1s infinite;
        }
        
        @keyframes blink {
          0%, 50% { opacity: 1; }
          51%, 100% { opacity: 0; }
        }
        
        .glitch-shadow {
          animation: glitch 3s infinite;
        }
        
        @keyframes glitch {
          0%, 100% { opacity: 0; }
          2%, 8% { opacity: 0.8; transform: translate(-2px, 0); }
          4%, 6% { opacity: 0.8; transform: translate(2px, 0); }
        }
        
        .line {
          stroke-dasharray: 400;
          stroke-dashoffset: 400;
          animation: draw 2s ease-in-out forwards;
        }
        
        @keyframes draw { to { stroke-dashoffset: 0; } }
        
        .fade-in {
          opacity: 0;
          animation: fadeIn 1s ease-in forwards;
        }
        
        @keyframes fadeIn { to { opacity: 1; } }
      </style>
    </defs>
    
    <!-- Background -->
    <rect width="800" height="400" fill="url(#bg)" rx="8"/>
    
    <!-- Decorative lines -->
    <line class="line" x1="50" y1="100" x2="750" y2="100" stroke="#00ff88" stroke-width="2" opacity="0.3"/>
    <line class="line" x1="50" y1="180" x2="750" y2="180" stroke="#ff0088" stroke-width="1" opacity="0.3" style="animation-delay: 0.3s"/>
    <line class="line" x1="50" y1="340" x2="750" y2="340" stroke="#00ff88" stroke-width="1" opacity="0.3" style="animation-delay: 0.6s"/>
    
    <!-- Glitch effect shadow -->
    <text class="title glitch-shadow" x="400" y="80" text-anchor="middle" fill="#ff0088" opacity="0.5">OMAR WAEL</text>
    
    <!-- Main title -->
    <text class="title" x="400" y="80" text-anchor="middle" filter="url(#glow)">OMAR WAEL</text>
    
    <!-- Subtitle -->
    <text class="subtitle fade-in" x="400" y="110" text-anchor="middle" style="animation-delay: 0.5s">Full-Stack Developer • DevOps Enthusiast • Powered by Coffee &amp; Linux</text>
    
    <!-- Terminal window -->
    <rect x="50" y="140" width="700" height="180" fill="#000000" stroke="#00ff88" stroke-width="2" rx="5" opacity="0.9"/>
    
    <!-- Terminal dots -->
    <circle cx="70" cy="160" r="4" fill="#00ff88"/>
    <circle cx="85" cy="160" r="4" fill="#00ff88"/>
    <circle cx="100" cy="160" r="4" fill="#00ff88"/>
    
    <!-- Terminal content -->
    <text class="terminal-text fade-in" x="70" y="195" style="animation-delay: 0.8s">omar@linux-box:~$</text>
    <text class="terminal-text fade-in" x="210" y="195" fill="#ff0088" style="animation-delay: 1s">cat skills.txt</text>
    
    <text class="output-text fade-in" x="90" y="220" style="animation-delay: 1.2s">→ Crafting robust backend logic with Python (Django / FastAPI)</text>
    <text class="output-text fade-in" x="90" y="240" style="animation-delay: 1.4s">→ Building modern, dynamic frontends with React</text>
    <text class="output-text fade-in" x="90" y="260" style="animation-delay: 1.6s">→ Containerizing apps &amp; orchestrating with Docker &amp; Kubernetes</text>
    <text class="output-text fade-in" x="90" y="280" style="animation-delay: 1.8s">→ Automation via Bash scripting &amp; Linux environment optimization</text>
    
    <text class="terminal-text fade-in" x="70" y="305" style="animation-delay: 2s">omar@linux-box:~$</text>
    <rect class="blink" x="210" y="290" width="10" height="18" fill="#00ff88" style="animation-delay: 2.2s"/>
    
    <!-- Tech tags -->
    <g class="fade-in" style="animation-delay: 2.2s">
      <rect x="65" y="350" width="90" height="25" rx="12" fill="none" stroke="#00ff88" stroke-width="1.5"/>
      <text x="110" y="368" font-family="'Courier New', monospace" font-size="12" fill="#00ff88" text-anchor="middle">Python</text>
    </g>
    
    <g class="fade-in" style="animation-delay: 2.3s">
      <rect x="165" y="350" width="90" height="25" rx="12" fill="none" stroke="#00ff88" stroke-width="1.5"/>
      <text x="210" y="368" font-family="'Courier New', monospace" font-size="12" fill="#00ff88" text-anchor="middle">Django</text>
    </g>
    
    <g class="fade-in" style="animation-delay: 2.4s">
      <rect x="265" y="350" width="90" height="25" rx="12" fill="none" stroke="#00ff88" stroke-width="1.5"/>
      <text x="310" y="368" font-family="'Courier New', monospace" font-size="12" fill="#00ff88" text-anchor="middle">React</text>
    </g>
    
    <g class="fade-in" style="animation-delay: 2.5s">
      <rect x="365" y="350" width="90" height="25" rx="12" fill="none" stroke="#00ff88" stroke-width="1.5"/>
      <text x="410" y="368" font-family="'Courier New', monospace" font-size="12" fill="#00ff88" text-anchor="middle">Docker</text>
    </g>
    
    <g class="fade-in" style="animation-delay: 2.6s">
      <rect x="465" y="350" width="105" height="25" rx="12" fill="none" stroke="#00ff88" stroke-width="1.5"/>
      <text x="517" y="368" font-family="'Courier New', monospace" font-size="12" fill="#00ff88" text-anchor="middle">Kubernetes</text>
    </g>
    
    <g class="fade-in" style="animation-delay: 2.7s">
      <rect x="580" y="350" width="155" height="25" rx="12" fill="none" stroke="#ff0088" stroke-width="1.5"/>
      <text x="657" y="368" font-family="'Courier New', monospace" font-size="12" fill="#ff0088" text-anchor="middle">Struggler (Berserk)</text>
    </g>
  </svg>
</div>

###

<table width="100%" border="0" cellspacing="0" cellpadding="0">
  <tr>
    <td valign="top" width="65%">
      <h1 align="left">🐧 ~/ENG-Omar-Wael $ cat intro.md</h1>
      <p align="left">
        • <b>User:</b> Omar Wael <br>
        • <b>Type:</b> Full Stack Developer using Python <br>
        • <b>Status:</b> Crafting clean backend logic and building scalable web apps. <br>
        • <b>Toolbox:</b> Python, Django, Flask, FastAPI, JavaScript, React, jQuery, Bootstrap, HTML, CSS, PostgreSQL, MySQL, Linux, Bash, Git, Docker, Kubernetes.
      </p>
    </td>
    <td valign="middle" width="35%" align="right">
      <img height="220" src="https://media0.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3bWN3OGN0endlb3A4eWNpanAzdmkzaHZ4YWwwaXB4ODNjdTR4ejR1bCZlcD12MV9naWZzX3NlYXJjaCZjdD1n/yu3AjjPeLagnybzyuE/giphy.webp" />
    </td>
  </tr>
</table>

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="32" alt="javascript logo" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="32" alt="html5 logo" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="32" alt="css3 logo" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="32" alt="python logo" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" height="32" alt="postgresql logo" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flask/flask-original.svg" height="32" alt="flask logo" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/django/django-plain.svg" height="32" alt="django logo" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" height="32" alt="fastapi logo" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="32" alt="react logo" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jquery/jquery-original.svg" height="32" alt="jquery logo" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" height="32" alt="bootstrap logo" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" height="32" alt="mysql logo" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sqlalchemy/sqlalchemy-original.svg" height="32" alt="sqlalchemy logo" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" height="32" alt="linux logo" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" height="32" alt="bash logo" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" height="32" alt="git logo" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" height="32" alt="github logo" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" height="32" alt="docker logo" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-plain.svg" height="32" alt="kubernetes logo" />
</div>

###

<div align="left">
  <a href="https://www.linkedin.com/in/omarwaelkishk" target="_blank">
    <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&style=for-the-badge" height="35" alt="linkedin logo" />
  </a>
  <a href="https://web.facebook.com/omar.wael.931356/" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Facebook&logo=facebook&label=&color=1877F2&logoColor=white&style=for-the-badge" height="35" alt="facebook logo" />
  </a>
  <a href="mailto:owael2003@gmail.com" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Gmail&logo=gmail&label=&color=D14836&logoColor=white&style=for-the-badge" height="35" alt="gmail logo" />
  </a>
</div>

###

<br>
<div align="center">
  <table border="0" cellpadding="2" cellspacing="2" align="center">
    <tr>
      <td align="center"><img height="110" src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExZmhvZmFyZGQybm9iY2MwZGczcWJ1dm84aWZmeWR6MWxiaDh0N2tyNSZlcD12MV9naWZzX3NlYXJjaCZjdD1n/EaEWuES5SDSpcnOlRt/200.webp" /></td>
      <td align="center"><img height="110" src="https://media3.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3c2ZqeXBiMHFpYW1yY3Q4djdpMjRkZHV5bTh1eW9meDFpMWZ0ZTgzdCZlcD12MV9naWZzX3NlYXJjaCZjdD1n/S9d8XB557e8phGLBVS/giphy.webp" /></td>
      <td align="center"><img height="110" src="https://media2.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3bDNpeTFiZHdzOWxpNjdjYXlsemN2Mjl3cDVkZTJkMWs5NXl0dnJzMSZlcD12MV9naWZzX3NlYXJjaCZjdD1n/0eIgxkeDtLSbWLkOAc/giphy.webp" /></td>
      <td align="center"><img height="110" src="https://media1.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3ZXJyN3dnb28zZWtneDFsb3FhbnFkaGdwN2U3bjZzMnJnN3EwZ2JvbyZlcD12MV9naWZzX3NlYXJjaCZjdD1n/pbIavlMZE7TkcVriMM/giphy.webp" /></td>
    </tr>
    <tr>
      <td align="center"><img height="110" src="https://media1.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3c2ZqeXBiMHFpYW1yY3Q4djdpMjRkZHV5bTh1eW9meDFpMWZ0ZTgzdCZlcD12MV9naWZzX3NlYXJjaCZjdD1n/DX1cytoIQvnmgqBlQ3/giphy.webp" /></td>
      <td align="center"><img height="110" src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExcXN5ZDM0NWJsNGc2NHl1endpY3J1dmh5bDhxaHBxbzhldmF2bHdieSZlcD12MV9naWZzX3NlYXJjaCZjdD1n/66M6ZwJkTLYikvhrqZ/giphy.webp" /></td>
      <td align="center"><img height="110" src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExcXN5ZDM0NWJsNGc2NHl1endpY3J1dmh5bDhxaHBxbzhldmF2bHdieSZlcD12MV9naWZzX3NlYXJjaCZjdD1n/GghGKaZ8JeHJx0apQC/giphy.webp" /></td>
      <td align="center"><img height="110" src="https://media4.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3ZmtuOW5vaXA4cHBndmFtcDhubXpvOGVhZDdjaG12MzVxeDJtdm9layZlcD12MV9naWZzX3NlYXJjaCZjdD1n/fha1cv4Le2lVRXXJsc/giphy.webp" /></td>
    </tr>
  </table>
</div>
<br>

###

<div>
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=100&section=footer&reversal=false&fontSize=70&fontColor=FFFFFF&fontAlign=50&fontAlignY=50&stroke=-&animation=scaleIn&descSize=20&descAlign=50&descAlignY=50&theme=dark" />
</div>
