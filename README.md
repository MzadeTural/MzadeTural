from pathlib import Path

<h2 align="left">Hi 👋 I’m @MzadeTural</h2>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=MzadeTural&show_icons=true&theme=dark&hide_border=true&count_private=true" alt="GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MzadeTural&layout=compact&theme=dark&hide_border=true" alt="Top languages" />
</p>

## 🛠️ Technologies

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="45" height="45" alt="JavaScript" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="45" height="45" alt="TypeScript" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="45" height="45" alt="React" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="45" height="45" alt="HTML5" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="45" height="45" alt="CSS3" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" width="45" height="45" alt="C#" />
</p>

## 📫 Connect with me

<p align="left">
  <a href="https://www.instagram.com/MzadeTural" target="_blank">
    <img src="https://img.shields.io/badge/INSTAGRAM-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" />
  </a>
  <a href="mailto:your-email@example.com">
    <img src="https://img.shields.io/badge/GMAIL-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
  </a>
  <a href="https://www.linkedin.com/in/MzadeTural/" target="_blank">
    <img src="https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</p>

## 🐍 Contribution Snake

<p align="center">
  <img src="https://raw.githubusercontent.com/MzadeTural/MzadeTural/output/github-contribution-grid-snake.svg" alt="GitHub contribution snake animation" />
</p>
"""

path = Path("/mnt/data/README.md")
path.write_text(readme, encoding="utf-8")

print(f"Created: {path}")
