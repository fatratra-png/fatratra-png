<div align="center">

<!-- Animated header banner with bubble font via custom style -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:c4b5fd,50:f9a8d4,100:93c5fd&height=220&section=header&text=Hi%2C%20I%27m%20Fatratra%20%F0%9F%91%8B&fontSize=46&fontColor=ffffff&fontAlignY=38&desc=Frontend%20Dev%20%E2%80%A2%20UI%20Designer%20%E2%80%A2%20Still%20figuring%20it%20out%20%F0%9F%8C%B1&descAlignY=58&descSize=16&descColor=ede9fe&animation=fadeIn&fontFamily=Nunito" alt="Header Banner"/>

<!-- Animated typing SVG -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Nunito&weight=800&size=22&duration=3000&pause=800&color=7C3AED&center=true&vCenter=true&multiline=false&width=500&lines=Somewhere+between+designer+%26+dev+%F0%9F%92%AB;Design+first%2C+then+code.+Deal+with+it.+%F0%9F%8E%A8;Frontend+%E2%86%92+Backend+%F0%9F%8F%8A;React+%7C+Tailwind+%7C+Figma+%7C+Node.js" alt="Typing SVG"/>
</a>

<br/>

<!-- Profile views counter -->
<img src="https://komarev.com/ghpvc/?username=fatratra-png&label=Profile+views&color=a78bfa&style=for-the-badge" alt="Profile Views"/>

</div>

---

## 💻 About me

```javascript
const about = {
  role:       ["Frontend Developer", "UI Designer", "Mobile Dev (in progress)"],
  currently:  "Comfortable with frontend & UI — now diving into backend 🏊",
  learning:   ["React Native", "Node.js", "deeper SQL"],
  philosophy: "If it doesn't look good, it doesn't ship.",
  funFact:    "I design first, then code. Deal with it."
};
```

---

## 🛠️ Tech Stack

<div align="center">

**✦ Frontend & Design ✦**

![HTML5](https://img.shields.io/badge/HTML5-EA580C?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-2563EB?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-0EA5E9?style=for-the-badge&logo=react&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-10B981?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-D946EF?style=for-the-badge&logo=figma&logoColor=white)

**✦ Backend & Data ✦**

![Python](https://img.shields.io/badge/Python-3B82F6?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-7C3AED?style=for-the-badge&logo=postgresql&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-16A34A?style=for-the-badge&logo=nodedotjs&logoColor=white)

**✦ Tools & Deployment ✦**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-1E293B?style=for-the-badge&logo=github&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

**✦ Exploring Next ✦**

![React Native](https://img.shields.io/badge/React_Native-0284C7?style=for-the-badge&logo=react&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-64748B?style=for-the-badge&logo=express&logoColor=white)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=fatratra-png&show_icons=true&theme=tokyonight&bg_color=0d0d1a&title_color=a78bfa&icon_color=f472b6&text_color=e2d9f3&border_color=4c1d95&border_radius=16&hide_border=false&card_width=400" alt="GitHub Stats"/>

<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=fatratra-png&layout=compact&theme=tokyonight&bg_color=0d0d1a&title_color=a78bfa&text_color=e2d9f3&border_color=4c1d95&border_radius=16&langs_count=6" alt="Top Languages"/>

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=fatratra-png&theme=tokyonight&background=0d0d1a&ring=a78bfa&fire=f472b6&currStreakLabel=a78bfa&sideLabels=e2d9f3&dates=6d6d8a&border=4c1d95&border_radius=16" alt="GitHub Streak"/>

</div>

---

## 🐍 Contribution Snake

> **Setup:** Add the workflow below as `.github/workflows/snake.yml` to generate your snake animation automatically.

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/fatratra-png/fatratra-png/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/fatratra-png/fatratra-png/output/github-contribution-grid-snake.svg"/>
  <img alt="Contribution Snake" src="https://raw.githubusercontent.com/fatratra-png/fatratra-png/output/github-contribution-grid-snake.svg"/>
</picture>

</div>

<details>
<summary><b>⚙️ snake.yml — click to expand</b></summary>

```yaml
# .github/workflows/snake.yml
name: Generate Snake Animation

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:
  push:
    branches:
      - main

jobs:
  generate:
    runs-on: ubuntu-latest
    timeout-minutes: 10

    steps:
      - name: Generate snake animation
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: Push output to output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

</details>

---

## 🌱 Currently

- 🎨 Comfortable with **frontend** & **UI design** — always leveling up
- 📱 Dipping into **mobile development** with React Native
- 🔧 Curious about what lives behind the API — exploring **backend**
- 🚀 Building my **portfolio** soon — stay tuned

---

## 🤝 Let's Connect

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-Coming%20Soon%20✨-A78BFA?style=for-the-badge&logo=vercel&logoColor=white)](https://github.com/fatratra-png)
[![GitHub](https://img.shields.io/badge/GitHub-fatratra--png-1E293B?style=for-the-badge&logo=github&logoColor=white)](https://github.com/fatratra-png)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:93c5fd,50:f9a8d4,100:c4b5fd&height=140&section=footer&fontFamily=Nunito" alt="Footer Banner"/>

</div>
