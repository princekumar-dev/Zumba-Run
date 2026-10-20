<div align="center">

# Zumba Run

### A retro endless runner — in a single HTML file.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/Vanilla-JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/docs/Web/JavaScript)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/docs/Web/CSS)
[![Dependencies](https://img.shields.io/badge/Dependencies-0-brightgreen?style=flat-square)](#-project-structure)
[![Pages](https://img.shields.io/badge/GitHub-Pages-222222?style=flat-square&logo=githubpages&logoColor=white)](https://princekumar-dev.github.io/Zumba-Run/)

**[🎮 Play Now](https://princekumar-dev.github.io/Zumba-Run/)**

</div>

## 🎯 Overview

**Zumba Run** is a Chrome-Dino-style **endless runner** built with plain HTML, CSS, and JavaScript — **one file, zero dependencies, no build step**. Run, jump, and shoot your way through an ever-faster obstacle course while racking up coins and power-ups across four changing biomes.

Drop `index.html` in any browser and it plays. That's the whole install.

## ✨ Features

### 🌵 Core Gameplay
- **Run & jump** over pipes, bushes, and cacti as the speed ramps up
- **Shoot obstacles** (`F` / on-screen fire button) to clear the path
- **Lives + protection power-ups** — survive hits and keep your run alive
- **Coins** scattered along the course to boost your score
- **Difficulty curve** — speed increases the longer you survive

### 🎨 Four Biomes
Dynamic theme transitions between **Desert 🏜️**, **Ice ❄️**, **Lava 🌋**, and **Night 🌙** — each with its own sky, terrain, and obstacle styling.

### 🏆 Scoring & Persistence
- Live score counter with animated coin tally
- **High score saved to `localStorage`** — beat your best every run
- Game-over screen with instant restart

### 🎮 Controls & Modes
- **Pause** any time with `P`
- **Retro arcade feel** with the *Press Start 2P* pixel font and sound effects
- **Fully responsive** — on-screen jump/shoot buttons adapt to mobile and orientation changes

## 🕹️ Controls

| Action | Keyboard | Touch |
|--------|----------|-------|
| Jump / Restart | `Space` | Jump button |
| Shoot | `F` | Fire button |
| Pause / Resume | `P` | — |

## 🧱 Project Structure

```
Zumba-Run/
├── index.html          # The entire game (markup + styles + logic)
├── README.md
└── .github/
    └── workflows/
        └── static.yml  # Auto-deploys to GitHub Pages on push
```

## ▶️ Run Locally

No install, no build:

```bash
git clone https://github.com/princekumar-dev/Zumba-Run.git
cd Zumba-Run
start index.html        # Windows — or just double-click the file
```

…or serve it if you prefer:

```bash
npx serve .
```

## ☁️ Deployment

The game deploys itself: [`.github/workflows/static.yml`](.github/workflows/static.yml) publishes to **GitHub Pages** on every push to `main`. Update the game, push, and it's live in under a minute at:

**https://princekumar-dev.github.io/Zumba-Run/**

## 💡 Ideas for the Next Level

- [ ] Daily challenges and leaderboard
- [ ] New power-ups (magnet, 2× points)
- [ ] Character skins and animated sprites
- [ ] PWA support for offline play

## 📄 License

All rights reserved.
