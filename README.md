<div align="center">
  
<!-- Cosmic Background Banner with Floating Particles -->
<svg width="100%" height="400" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 400">
  <defs>
    <radialGradient id="nebula1">
      <stop offset="0%" style="stop-color:#00f5ff;stop-opacity:0.15"/>
      <stop offset="100%" style="stop-color:#000000;stop-opacity:0"/>
    </radialGradient>
    <radialGradient id="nebula2">
      <stop offset="0%" style="stop-color:#7b2ff7;stop-opacity:0.12"/>
      <stop offset="100%" style="stop-color:#000000;stop-opacity:0"/>
    </radialGradient>
    <radialGradient id="nebula3">
      <stop offset="0%" style="stop-color:#f72585;stop-opacity:0.1"/>
      <stop offset="100%" style="stop-color:#000000;stop-opacity:0"/>
    </radialGradient>
    <filter id="starGlow">
      <feGaussianBlur stdDeviation="1.5" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  <rect width="1200" height="400" fill="#000000"/>
  <circle cx="200" cy="150" r="250" fill="url(#nebula1)">
    <animate attributeName="cx" values="200;250;200" dur="20s" repeatCount="indefinite"/>
    <animate attributeName="cy" values="150;180;150" dur="25s" repeatCount="indefinite"/>
    <animate attributeName="r" values="250;280;250" dur="15s" repeatCount="indefinite"/>
  </circle>
  <circle cx="800" cy="250" r="280" fill="url(#nebula2)">
    <animate attributeName="cx" values="800;750;800" dur="22s" repeatCount="indefinite"/>
    <animate attributeName="cy" values="250;220;250" dur="28s" repeatCount="indefinite"/>
    <animate attributeName="r" values="280;310;280" dur="18s" repeatCount="indefinite"/>
  </circle>
  <circle cx="500" cy="100" r="200" fill="url(#nebula3)">
    <animate attributeName="cx" values="500;550;500" dur="24s" repeatCount="indefinite"/>
    <animate attributeName="cy" values="100;130;100" dur="20s" repeatCount="indefinite"/>
    <animate attributeName="r" values="200;230;200" dur="16s" repeatCount="indefinite"/>
  </circle>
  <circle cx="1000" cy="100" r="220" fill="url(#nebula1)">
    <animate attributeName="cx" values="1000;950;1000" dur="26s" repeatCount="indefinite"/>
    <animate attributeName="cy" values="100;130;100" dur="23s" repeatCount="indefinite"/>
  </circle>
  <g filter="url(#starGlow)">
    <circle cx="150" cy="80" r="1.5" fill="#00f5ff" opacity="0.8">
      <animate attributeName="cy" values="80;90;80" dur="6s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.5;1;0.5" dur="6s" repeatCount="indefinite"/>
    </circle>
    <circle cx="320" cy="180" r="1.2" fill="#00f5ff" opacity="0.7">
      <animate attributeName="cy" values="180;170;180" dur="7s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.4;0.9;0.4" dur="7s" repeatCount="indefinite"/>
    </circle>
    <circle cx="580" cy="60" r="1.8" fill="#00f5ff" opacity="0.9">
      <animate attributeName="cy" values="60;70;60" dur="5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.6;1;0.6" dur="5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="750" cy="320" r="1.3" fill="#00f5ff" opacity="0.6">
      <animate attributeName="cy" values="320;310;320" dur="8s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.3;0.8;0.3" dur="8s" repeatCount="indefinite"/>
    </circle>
    <circle cx="920" cy="150" r="1.6" fill="#00f5ff" opacity="0.8">
      <animate attributeName="cy" values="150;160;150" dur="6.5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.5;1;0.5" dur="6.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="1050" cy="280" r="1.4" fill="#00f5ff" opacity="0.7">
      <animate attributeName="cy" values="280;270;280" dur="7.5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.4;0.9;0.4" dur="7.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="240" cy="250" r="1.4" fill="#7b2ff7" opacity="0.7">
      <animate attributeName="cy" values="250;240;250" dur="7s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.4;0.9;0.4" dur="7s" repeatCount="indefinite"/>
    </circle>
    <circle cx="450" cy="300" r="1.7" fill="#7b2ff7" opacity="0.8">
      <animate attributeName="cy" values="300;310;300" dur="6s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.5;1;0.5" dur="6s" repeatCount="indefinite"/>
    </circle>
    <circle cx="680" cy="120" r="1.3" fill="#7b2ff7" opacity="0.6">
      <animate attributeName="cy" values="120;130;120" dur="8s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.3;0.8;0.3" dur="8s" repeatCount="indefinite"/>
    </circle>
    <circle cx="850" cy="80" r="1.5" fill="#7b2ff7" opacity="0.8">
      <animate attributeName="cy" values="80;90;80" dur="5.5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.5;1;0.5" dur="5.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="1100" cy="200" r="1.6" fill="#7b2ff7" opacity="0.7">
      <animate attributeName="cy" values="200;190;200" dur="7s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.4;0.9;0.4" dur="7s" repeatCount="indefinite"/>
    </circle>
    <circle cx="180" cy="340" r="1.5" fill="#f72585" opacity="0.8">
      <animate attributeName="cy" values="340;330;340" dur="6.5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.5;1;0.5" dur="6.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="380" cy="100" r="1.3" fill="#f72585" opacity="0.7">
      <animate attributeName="cy" values="100;110;100" dur="7.5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.4;0.9;0.4" dur="7.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="620" cy="280" r="1.6" fill="#f72585" opacity="0.8">
      <animate attributeName="cy" values="280;270;280" dur="6s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.5;1;0.5" dur="6s" repeatCount="indefinite"/>
    </circle>
    <circle cx="780" cy="180" r="1.4" fill="#f72585" opacity="0.7">
      <animate attributeName="cy" values="180;190;180" dur="8s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.4;0.9;0.4" dur="8s" repeatCount="indefinite"/>
    </circle>
    <circle cx="980" cy="320" r="1.7" fill="#f72585" opacity="0.8">
      <animate attributeName="cy" values="320;310;320" dur="5.5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.5;1;0.5" dur="5.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="100" cy="200" r="1.2" fill="#ffffff" opacity="0.6">
      <animate attributeName="cy" values="200;210;200" dur="8s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.3;0.8;0.3" dur="8s" repeatCount="indefinite"/>
    </circle>
    <circle cx="280" cy="50" r="1.4" fill="#ffffff" opacity="0.7">
      <animate attributeName="cy" values="50;60;50" dur="7s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.4;0.9;0.4" dur="7s" repeatCount="indefinite"/>
    </circle>
    <circle cx="520" cy="220" r="1.6" fill="#ffffff" opacity="0.8">
      <animate attributeName="cy" values="220;210;220" dur="6s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.5;1;0.5" dur="6s" repeatCount="indefinite"/>
    </circle>
    <circle cx="720" cy="40" r="1.3" fill="#ffffff" opacity="0.7">
      <animate attributeName="cy" values="40;50;40" dur="7.5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.4;0.9;0.4" dur="7.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="890" cy="240" r="1.5" fill="#ffffff" opacity="0.8">
      <animate attributeName="cy" values="240;230;240" dur="6.5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.5;1;0.5" dur="6.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="1150" cy="120" r="1.4" fill="#ffffff" opacity="0.7">
      <animate attributeName="cy" values="120;130;120" dur="8s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.4;0.9;0.4" dur="8s" repeatCount="indefinite"/>
    </circle>
  </g>
  <g opacity="0.5">
    <circle cx="200" cy="120" r="0.8" fill="#00f5ff">
      <animate attributeName="cy" values="120;130;120" dur="9s" repeatCount="indefinite"/>
    </circle>
    <circle cx="350" cy="280" r="0.8" fill="#7b2ff7">
      <animate attributeName="cy" values="280;270;280" dur="10s" repeatCount="indefinite"/>
    </circle>
    <circle cx="550" cy="150" r="0.8" fill="#f72585">
      <animate attributeName="cy" values="150;160;150" dur="8.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="700" cy="220" r="0.8" fill="#ffffff">
      <animate attributeName="cy" values="220;210;220" dur="9.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="900" cy="90" r="0.8" fill="#00f5ff">
      <animate attributeName="cy" values="90;100;90" dur="8s" repeatCount="indefinite"/>
    </circle>
    <circle cx="1080" cy="340" r="0.8" fill="#7b2ff7">
      <animate attributeName="cy" values="340;330;340" dur="10s" repeatCount="indefinite"/>
    </circle>
  </g>
</svg>

<!-- Personal Logo -->
<svg width="300" height="300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 400 400">
  <defs>
    <linearGradient id="holoGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#00f5ff;stop-opacity:1">
        <animate attributeName="stop-color" values="#00f5ff;#7b2ff7;#f72585;#00f5ff" dur="6s" repeatCount="indefinite"/>
      </stop>
      <stop offset="50%" style="stop-color:#7b2ff7;stop-opacity:1">
        <animate attributeName="stop-color" values="#7b2ff7;#f72585;#00f5ff;#7b2ff7" dur="6s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" style="stop-color:#f72585;stop-opacity:1">
        <animate attributeName="stop-color" values="#f72585;#00f5ff;#7b2ff7;#f72585" dur="6s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="5" result="coloredBlur"/>
      <feGaussianBlur stdDeviation="10" result="coloredBlur2"/>
      <feMerge>
        <feMergeNode in="coloredBlur2"/>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="innerGlow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  <rect width="400" height="400" fill="#000000"/>
  <g transform="translate(200, 200)">
    <polygon points="0,-120 103.92,-60 103.92,60 0,120 -103.92,60 -103.92,-60" 
             fill="none" stroke="url(#holoGrad)" stroke-width="3" opacity="0.4" filter="url(#glow)">
      <animateTransform attributeName="transform" type="rotate" 
                        from="0 0 0" to="360 0 0" dur="20s" repeatCount="indefinite"/>
    </polygon>
  </g>
  <g transform="translate(200, 200)">
    <polygon points="0,-90 77.94,-45 77.94,45 0,90 -77.94,45 -77.94,-45" 
             fill="none" stroke="url(#holoGrad)" stroke-width="2.5" opacity="0.6">
      <animateTransform attributeName="transform" type="rotate" 
                        from="360 0 0" to="0 0 0" dur="15s" repeatCount="indefinite"/>
    </polygon>
  </g>
  <g transform="translate(200, 200)">
    <g stroke="url(#holoGrad)" stroke-width="2.5" fill="none" filter="url(#innerGlow)">
      <path d="M -30,-15 L 30,-15 L 30,45 L -30,45 Z" opacity="0.8"/>
      <path d="M -15,-30 L 45,-30 L 45,30 L -15,30 Z" opacity="0.6"/>
      <line x1="-30" y1="-15" x2="-15" y2="-30" opacity="0.7"/>
      <line x1="30" y1="-15" x2="45" y2="-30" opacity="0.7"/>
      <line x1="30" y1="45" x2="45" y2="30" opacity="0.7"/>
      <line x1="-30" y1="45" x2="-15" y2="30" opacity="0.7"/>
    </g>
    <g fill="none" stroke="url(#holoGrad)" stroke-width="4" stroke-linecap="round" filter="url(#glow)">
      <path d="M -55,-25 L -70,-25 L -70,25 L -55,25">
        <animate attributeName="opacity" values="0.6;1;0.6" dur="3s" repeatCount="indefinite"/>
      </path>
      <path d="M 55,-25 L 70,-25 L 70,25 L 55,25">
        <animate attributeName="opacity" values="0.6;1;0.6" dur="3s" repeatCount="indefinite" begin="1.5s"/>
      </path>
    </g>
    <g fill="url(#holoGrad)" opacity="0.8">
      <rect x="-5" y="-65" width="10" height="15" rx="2">
        <animate attributeName="opacity" values="0.5;1;0.5" dur="4s" repeatCount="indefinite"/>
      </rect>
      <rect x="-5" y="50" width="10" height="15" rx="2">
        <animate attributeName="opacity" values="0.5;1;0.5" dur="4s" repeatCount="indefinite" begin="2s"/>
      </rect>
      <rect x="-72" y="-5" width="15" height="10" rx="2">
        <animate attributeName="opacity" values="0.5;1;0.5" dur="4s" repeatCount="indefinite" begin="1s"/>
      </rect>
      <rect x="57" y="-5" width="15" height="10" rx="2">
        <animate attributeName="opacity" values="0.5;1;0.5" dur="4s" repeatCount="indefinite" begin="3s"/>
      </rect>
    </g>
    <circle cx="0" cy="0" r="15" fill="url(#holoGrad)" filter="url(#glow)">
      <animate attributeName="r" values="15;20;15" dur="2s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.8;1;0.8" dur="2s" repeatCount="indefinite"/>
    </circle>
    <circle cx="0" cy="0" r="8" fill="#ffffff" opacity="0.9">
      <animate attributeName="r" values="8;10;8" dur="2s" repeatCount="indefinite"/>
    </circle>
    <g>
      <circle cx="0" cy="-50" r="3" fill="#00f5ff" filter="url(#innerGlow)">
        <animateTransform attributeName="transform" type="rotate" 
                          from="0 0 0" to="360 0 0" dur="4s" repeatCount="indefinite"/>
      </circle>
      <circle cx="0" cy="-50" r="3" fill="#f72585" filter="url(#innerGlow)">
        <animateTransform attributeName="transform" type="rotate" 
                          from="120 0 0" to="480 0 0" dur="4s" repeatCount="indefinite"/>
      </circle>
      <circle cx="0" cy="-50" r="3" fill="#7b2ff7" filter="url(#innerGlow)">
        <animateTransform attributeName="transform" type="rotate" 
                          from="240 0 0" to="600 0 0" dur="4s" repeatCount="indefinite"/>
      </circle>
    </g>
  </g>
  <g stroke="url(#holoGrad)" stroke-width="2" opacity="0.5">
    <line x1="20" y1="20" x2="50" y2="20"/>
    <line x1="20" y1="20" x2="20" y2="50"/>
    <line x1="380" y1="20" x2="350" y2="20"/>
    <line x1="380" y1="20" x2="380" y2="50"/>
    <line x1="20" y1="380" x2="50" y2="380"/>
    <line x1="20" y1="380" x2="20" y2="350"/>
    <line x1="380" y1="380" x2="350" y2="380"/>
    <line x1="380" y1="380" x2="380" y2="350"/>
  </g>
  <g opacity="0.6">
    <circle cx="80" cy="80" r="2" fill="#00f5ff">
      <animate attributeName="opacity" values="0.3;0.8;0.3" dur="3s" repeatCount="indefinite"/>
    </circle>
    <circle cx="320" cy="80" r="2" fill="#f72585">
      <animate attributeName="opacity" values="0.3;0.8;0.3" dur="3s" repeatCount="indefinite" begin="1s"/>
    </circle>
    <circle cx="80" cy="320" r="2" fill="#7b2ff7">
      <animate attributeName="opacity" values="0.3;0.8;0.3" dur="3s" repeatCount="indefinite" begin="2s"/>
    </circle>
    <circle cx="320" cy="320" r="2" fill="#00f5ff">
      <animate attributeName="opacity" values="0.3;0.8;0.3" dur="3s" repeatCount="indefinite" begin="1.5s"/>
    </circle>
  </g>
</svg>

</div>

<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&duration=3000&pause=1000&color=00F7FF&center=true&vCenter=true&width=500&lines=Hey+there!+%F0%9F%91%8B;I'm+Gaurav+Singh;Full+Stack+Developer+%F0%9F%9A%80;Game+Developer+%F0%9F%8E%AE;3D+Artist+%F0%9F%8E%A8;AI%2FML+Enthusiast+%F0%9F%A4%96" alt="Typing SVG" />
</h1>

<p align="center">
  <a href="https://github.com/GAuravgiy87">
    <img src="https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="mailto:gauravchauhan292005@gmail.com">
    <img src="https://img.shields.io/badge/-Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=GAuravgiy87&label=Profile%20Views&color=00F7FF&style=for-the-badge" alt="Profile Views" />
</p>

<p align="center">
  <img src="https://github.com/GAuravgiy87/GAuravgiy87/blob/output/github-contribution-grid-snake-dark.svg" alt="Snake animation" />
</p>

<p align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="700">
</p>

<div align="center">

## 🚀 About Me

<img src="https://user-images.githubusercontent.com/74038190/225813708-98b745f2-7d22-48cf-9150-083f1b00d6c9.gif" width="500">

</div>

<table>
<tr>
<td width="50%">

<img src="https://user-images.githubusercontent.com/74038190/229223263-cf2e4b07-2615-4f87-9c38-e37600f8381a.gif" width="100%">

</td>
<td width="50%">

### �‍💻 Who Am I?

```javascript
const gaurav = {
    role: "Full Stack Developer",
    specialties: ["Game Dev", "3D Artist", "AI/ML"],
    currentFocus: "Building innovative solutions",
    funFact: "I turn ☕ into <code/>",
    motto: "Code. Debug. Design. Repeat."
};
```

### 🎯 What I Do

🔹 **Web Development** - Crafting scalable applications  
🔹 **Game Development** - Creating immersive experiences  
🔹 **3D Modeling** - Designing stunning visuals  
🔹 **AI/ML** - Building intelligent solutions  

</td>
</tr>
</table>

<p align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284158-e840e285-664b-44d7-b79b-e264b5e54825.gif" width="400">
</p>

<img src="https://user-images.githubusercontent.com/74038190/212284087-bbe7e430-757e-4901-90bf-4cd2ce3e1852.gif" width="100%">

<div align="center">

## 🛠️ Tech Arsenal

<img src="https://techstack-generator.vercel.app/python-icon.svg" alt="Python" width="65" height="65" />
<img src="https://techstack-generator.vercel.app/js-icon.svg" alt="JavaScript" width="65" height="65" />
<img src="https://techstack-generator.vercel.app/java-icon.svg" alt="Java" width="65" height="65" />
<img src="https://techstack-generator.vercel.app/cpp-icon.svg" alt="C++" width="65" height="65" />
<img src="https://techstack-generator.vercel.app/react-icon.svg" alt="React" width="65" height="65" />
<img src="https://techstack-generator.vercel.app/mysql-icon.svg" alt="MySQL" width="65" height="65" />
<img src="https://techstack-generator.vercel.app/docker-icon.svg" alt="Docker" width="65" height="65" />
<img src="https://techstack-generator.vercel.app/github-icon.svg" alt="GitHub" width="65" height="65" />

</div>

### 💻 Programming Languages
<p align="center">
  <img src="https://skillicons.dev/icons?i=python,js,java,cpp,c,cs&perline=6" />
</p>

### 🎨 Frontend Development
<p align="center">
  <img src="https://skillicons.dev/icons?i=react,nextjs,html,css,tailwind,bootstrap&perline=6" />
</p>

### ⚙️ Backend Development
<p align="center">
  <img src="https://skillicons.dev/icons?i=nodejs,django,flask&perline=3" />
</p>

### 🗄️ Databases
<p align="center">
  <img src="https://skillicons.dev/icons?i=mysql,mongodb,firebase&perline=3" />
</p>

### ☁️ Cloud & DevOps
<p align="center">
  <img src="https://skillicons.dev/icons?i=docker,git,github&perline=3" />
</p>

### 🎮 Game Development
<p align="center">
  <img src="https://skillicons.dev/icons?i=unity,godot,blender&perline=3" />
</p>

### 🤖 AI/ML & Data Science
<p align="center">
  <img src="https://skillicons.dev/icons?i=tensorflow,pytorch,opencv,sklearn&perline=4" />
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
</p>

### 🛠️ Tools & Technologies
<p align="center">
  <img src="https://skillicons.dev/icons?i=vscode,linux,postman&perline=3" />
</p>

<img src="https://user-images.githubusercontent.com/74038190/212284087-bbe7e430-757e-4901-90bf-4cd2ce3e1852.gif" width="100%">

## 📊 GitHub Analytics

<p align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=GAuravgiy87&show_icons=true&theme=radical&hide_border=true&count_private=true&bg_color=0D1117&title_color=00F7FF&icon_color=00F7FF&text_color=FFFFFF" alt="Gaurav's GitHub Stats" />
  <img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=GAuravgiy87&theme=radical&hide_border=true&background=0D1117&stroke=00F7FF&ring=00F7FF&fire=FF6D00&currStreakLabel=00F7FF" alt="GitHub Streak" />
</p>

<p align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=GAuravgiy87&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&title_color=00F7FF&text_color=FFFFFF&langs_count=10" alt="Top Languages" />
  <img width="49%" src="https://github-contributor-stats.vercel.app/api?username=GAuravgiy87&limit=5&theme=radical&hide_border=true&bg_color=0D1117&title_color=00F7FF&text_color=FFFFFF" alt="Top Contributed Repos" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=GAuravgiy87&theme=react-dark&hide_border=true&bg_color=0D1117&color=00F7FF&line=00F7FF&point=FFFFFF&area=true&area_color=00F7FF" alt="Contribution Graph" width="98%" />
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=GAuravgiy87&theme=radical&no-frame=true&no-bg=false&margin-w=4&row=1&column=7" alt="GitHub Trophies" />
</p>

<details>
  <summary><b>📈 More GitHub Metrics</b></summary>
  <br/>
  <p align="center">
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=GAuravgiy87&theme=radical" alt="Profile Details" />
  </p>
  <p align="center">
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=GAuravgiy87&theme=radical" alt="Repos per Language" />
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=GAuravgiy87&theme=radical" alt="Most Commit Language" />
  </p>
  <p align="center">
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=GAuravgiy87&theme=radical" alt="Stats" />
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=GAuravgiy87&theme=radical" alt="Productive Time" />
  </p>
</details>

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="100%">

## 🎮 Game Development Showcase

<p align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212748830-4c709398-a386-4761-84d7-9e10b98fbe6e.gif" width="400">
</p>

<table align="center">
  <tr>
    <td align="center" width="50%">
      <img src="https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white" /><br/>
      <sub><b>Game Engine</b></sub>
    </td>
    <td align="center" width="50%">
      <img src="https://img.shields.io/badge/Godot-478CBF?style=for-the-badge&logo=godot-engine&logoColor=white" /><br/>
      <sub><b>Indie Games</b></sub>
    </td>
  </tr>
</table>

### 🎨 3D Modeling & Design
<p align="center">
  <img src="https://img.shields.io/badge/Blender-F5792A?style=for-the-badge&logo=blender&logoColor=white" />
  <img src="https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white" />
</p>

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="100%">

## 🤖 AI/ML Projects

<p align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212749447-bfb7e725-6987-49d9-ae85-2015e3e7cc41.gif" width="400">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white" />
</p>

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="100%">

## 🌐 Connect With Me

<p align="center">
  <img src="https://user-images.githubusercontent.com/74038190/216122041-518ac897-8d92-4c6b-9b3f-ca01dcaf38ee.png" alt="Fire" width="100" />
</p>

<div align="center">

[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github&logoColor=white&link=https://github.com/GAuravgiy87)](https://github.com/GAuravgiy87)
[![Email](https://img.shields.io/badge/-Email-D14836?style=for-the-badge&logo=gmail&logoColor=white&link=mailto:gauravchauhan292005@gmail.com)](mailto:gauravchauhan292005@gmail.com)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/gaurav-singh)
[![Twitter](https://img.shields.io/badge/-Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/gauravsingh)
[![Instagram](https://img.shields.io/badge/-Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/gauravsingh)

</div>

<p align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284136-03988914-d899-44b4-b1d9-4eeccf656e44.gif" width="150">
  <img src="https://user-images.githubusercontent.com/74038190/212284136-03988914-d899-44b4-b1d9-4eeccf656e44.gif" width="150">
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer&text=Thanks%20for%20visiting!&fontSize=30&fontAlignY=70&animation=twinkling" width="100%">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Trilokia/Trilokia/379277808c61ef204768a61bbc5d25bc7798ccf1/bottom_header.svg" />
</p>
