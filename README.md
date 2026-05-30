# GLITCH
OTT platform 
# 🎬 GLITCH — OTT Streaming Platform UI

> A cinematic, dark-themed streaming platform frontend built with pure HTML, CSS, and JavaScript. No frameworks. No libraries. Just vibes.

---

## 📸 Overview

GLITCH is a college project that mimics the look and feel of a real OTT platform (think Netflix, but make it cooler). It showcases trending movies with an animated hero slider, critic scores, a cast spotlight, and fun facts — all wrapped in a sleek dark UI.

---

## ✨ Features

### 🎞️ Auto-Playing Hero Slider
- 4 featured movies: **Dune: Part Two**, **Alien: Romulus**, **Civil War**, and **Wicked**
- Slides auto-advance every 5 seconds with a smooth fade transition
- Manual navigation via arrow buttons and dot indicators
- Keyboard support — use arrow keys to go back and forward
- Subtle Ken Burns zoom effect on slide backgrounds

### 🔴 Live News Ticker
- Scrolling marquee banner with the latest movie buzz
- Runs on an infinite CSS animation loop

### 🏆 Critics Section
- Animated score bars for each movie with Rotten Tomatoes / critic ratings
- Cards lift on hover with a gradient underline reveal effect

### 🎭 Cast Spotlight
- Horizontally scrollable cast cards for all 8 featured actors
- **Click any actor's circle to open their Wikipedia page** in a new tab
- Gradient avatar rings appear on hover

### 💡 Hot Takes & Facts
- 6 fun fact cards covering box office numbers, behind-the-scenes trivia, and award season picks
- Color-coded by category (red, orange, green, purple, blue)

### ☁️ Cloud Tooltips on Buttons
- Hover **"Watch Now"** → cloud bubble appears: *"🎬 Switch it on Netflix"*
- Hover **"+ Watchlist"** → cloud bubble appears: *"🚧 Still working on it"*

### 📱 Fully Responsive
- **Desktop** — full layout with side card art and wide grids
- **Tablet (≤ 900px)** — scaled-down card art, 2-column grids, tighter padding
- **Mobile (≤ 600px)** — hamburger menu with full-screen nav overlay, single-column layout, card art hidden for clean readability

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Structure and semantics |
| CSS3 | Styling, animations, responsive layout |
| Vanilla JavaScript | Slider logic, keyboard nav, hamburger menu |
| Google Fonts | Bebas Neue, Space Grotesk, Syne |

Zero dependencies. No npm. No build step. Just open the file.

---

## 🚀 Getting Started

1. Download `Glitch_ott.html`
2. Open it in any modern browser
3. That's it

```bash
# Or serve it locally
npx serve .
# then open http://localhost:3000
```

---

## 📂 File Structure

```
Glitch_ott.html   ← Everything lives in one file
README.md         ← You're reading this
```

All CSS and JavaScript is embedded directly in the HTML file — no external assets required beyond Google Fonts.

---

## 🎨 Design Tokens

| Variable | Value | Used For |
|---|---|---|
| `--bg` | `#080808` | Page background |
| `--surface` | `#111111` | Cards, nav |
| `--accent` | `#ff2d55` | Primary red — logo, buttons, highlights |
| `--accent2` | `#ff9f0a` | Orange — ratings, score bars |
| `--accent3` | `#30d158` | Green — accents |
| `--text` | `#f5f5f5` | Body text |

---

## 🎬 Featured Content

| Movie | Year | Genre | Rating |
|---|---|---|---|
| Dune: Part Two | 2024 | Sci-Fi | ⭐ 8.8 |
| Alien: Romulus | 2024 | Horror | ⭐ 7.3 |
| Civil War | 2024 | Thriller | ⭐ 7.2 |
| Wicked | 2024 | Musical | ⭐ 7.6 |

---

## 🙋 About

Made with 💻 and too much caffeine by **Soumya Thamke** as a college project.

© 2023 GLITCH Platform
