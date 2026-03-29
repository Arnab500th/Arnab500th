<h1 align="center">Hey, I'm Arnab Datta 👋</h1>

<p align="center">
  <em>First-year CS student · Python · ML & Computer Vision · Building things that work in the real world</em>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=arnab500th&label=Profile%20views&color=0e75b6&style=flat" alt="arnab500th" />
</p>

<p align="center">
  <img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="480" alt="coding gif"/>
</p>

---

### About Me

I'm a Computer Science student at **St. Xavier's College, Burdwan** with a focus on machine learning, computer vision, and backend systems. I like understanding how things work under the hood — most of my projects start as a question and end up as something I didn't plan to build.

- 🔭 Currently interning at **Venture Launcher** — building ML pipelines and recommendation systems
- 🧪 Previously interned at **QSkill** — Python development, NLP, and ML models
- 🎨 Outside of code — I paint. Watercolour, oil, sketching. Occasionally wins things there too.
- 📍 Burdwan, West Bengal, India &nbsp;·&nbsp; 🤝 Open to internships and collaborations

---

### 🏆 Highlight

**[TRACE — Automated Littering Detection & Alert System](https://github.com/Arnab500th/Hackathon-Automated-Littering-Detection-and-Alert-System-for-Public-Spaces)**
🥈 **2nd Place — NextGenHack 2026**

Real-time AI surveillance pipeline — YOLOv8 + ByteTrack + 5-state machine + Haversine geofencing + Twilio WhatsApp alerts routed to the nearest municipality office by GPS. Built end-to-end in under 4 days.

---

### 🧰 Tech Stack

| Category | Technologies |
|---|---|
| 💻 **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white) |
| 🎨 **Frontend** | ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white) |
| ⚙️ **Backend** | ![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white) |
| 🤖 **AI / Machine Learning** | ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white) ![YOLOv8](https://img.shields.io/badge/YOLOv8-111111?style=flat&logo=yolo&logoColor=white) ![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=flat&logoColor=white) |
| 🗄 **Databases** | ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white) |
| ⚡ **Messaging** | ![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=flat&logo=twilio&logoColor=white) |
| 🛠 **Tools** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white) |

---

### 📌 Featured Projects

| Project | What it does |
|---|---|
| [TRACE](https://github.com/Arnab500th/Hackathon-Automated-Littering-Detection-and-Alert-System-for-Public-Spaces) | Real-time littering detection + WhatsApp alerts · 🥈 NextGenHack 2026 |
| [Subway Surfers Pose Control](https://github.com/Arnab500th/Subway-Surfers-Pose-Control-Game-Computer-Vision-) | Full-body gesture control via webcam using MediaPipe |
| [Computational String Art](https://github.com/Arnab500th/Computational-String-Art) | Greedy algorithm converts images into circular string art |
| [Speed Dating Compatibility Predictor](https://github.com/Arnab500th/Speed-Dating-Compatibility-Predictor) | ML model + Flask app to predict compatibility probability |

---

### 📊 GitHub Stats

<!-- 
  STATS SETUP (one-time):
  Create .github/workflows/grs.yml with the content in the collapsible below.
  After the workflow runs, these static SVG paths will work permanently.
-->

<p align="center">
  <img src="./profile/top-langs.svg" alt="top langs" />
</p>
<p align="center">
  <img src="./profile/stats.svg" alt="github stats" />
</p>
<p align="center">
  <img src="https://nirzak-streak-stats.vercel.app/?user=arnab500th&theme=tokyonight" alt="streak stats" />
</p>

<details>
<summary>⚙️ One-time setup: GitHub Actions for stats cards</summary>

Create `.github/workflows/grs.yml` in this repo:

```yaml
name: Update README cards

on:
  schedule:
    - cron: "0 3 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4

      - name: Generate stats card
        uses: readme-tools/github-readme-stats-action@v1
        with:
          card: stats
          options: username=arnab500th&show_icons=true&theme=tokyonight
          path: profile/stats.svg
          token: ${{ secrets.GITHUB_TOKEN }}

      - name: Generate top langs card
        uses: readme-tools/github-readme-stats-action@v1
        with:
          card: top-langs
          options: username=arnab500th&layout=compact&theme=tokyonight
          path: profile/top-langs.svg
          token: ${{ secrets.GITHUB_TOKEN }}

      - name: Commit cards
        run: |
          git config user.name "github-actions"
          git config user.email "github-actions@users.noreply.github.com"
          git add profile/*.svg
          git commit -m "Update README cards" || exit 0
          git push
```

After this runs once, the `./profile/stats.svg` and `./profile/top-langs.svg` paths in the README will work reliably forever.

</details>

---

### 🐍 Contribution Snake

<p align="center">
  <img src="./output/github-contribution-grid-snake-dark.svg#gh-dark-mode-only" alt="snake animation dark" />
  <img src="./output/github-contribution-grid-snake.svg#gh-light-mode-only" alt="snake animation light" />
</p>

<details>
<summary>⚙️ Fix snake not showing — check your workflow output path</summary>

The snake SVGs must be committed to a branch called `output` in **this same repo** (`arnab500th/arnab500th`). Your `.github/workflows/snake.yml` should look like this:

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: arnab500th
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

After saving, go to **Actions → Generate Snake → Run workflow** manually to trigger it. Once it runs, the `output` branch will be created and the SVGs will appear.

</details>

---

### 🌐 Connect

<p align="left">
  <a href="https://www.linkedin.com/in/arnab500th/" target="_blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="linkedin" height="30" width="40"/></a>
  <a href="https://www.youtube.com/c/arnab500th" target="_blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="youtube" height="30" width="40"/></a>
  <a href="https://twitter.com/arnab500th" target="_blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="twitter" height="30" width="40"/></a>
  <a href="https://instagram.com/arnab500th" target="_blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="instagram" height="30" width="40"/></a>
  <a href="https://www.leetcode.com/arnab500th" target="_blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/leet-code.svg" alt="leetcode" height="30" width="40"/></a>
  <a href="https://portfolio-8ph.pages.dev/" target="_blank"><img align="center" src="https://cdn-icons-png.flaticon.com/512/1154/1154313.png" alt="portfolio" height="30" width="40"/></a>
</p>

<p align="center">
  <img src="https://media.giphy.com/media/LnQjpWaON8nhr21vNW/giphy.gif" width="60">
  <em><b>I love connecting with different people</b> — feel free to reach out!</em>
</p>
