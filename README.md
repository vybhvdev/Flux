# ⚡ FLUX — Lights Out Puzzle

> *Turn off the grid. Embrace the dark.*

**FLUX** is a neon-soaked puzzle game based on the classic **Lights Out** mechanic.  
Tap a cell — it and its neighbors flip. Your mission: turn every light **OFF**.  
Simple rules. Endless challenge.

**Play it in your browser — or download the Android app.**

---

## 🌐 Play Online

[![Play Now](https://img.shields.io/badge/PLAY%20NOW-GitHub%20Pages-e8ff47?style=for-the-badge&labelColor=0a0a0f)](https://vybhvdev.github.io/Flux/)

No install. No account. Just open and play.

---

## 📱 Download Android APK

[![Latest Release](https://img.shields.io/github/v/release/YOUR_USERNAME/YOUR_REPO?style=for-the-badge&color=e8ff47&labelColor=0a0a0f&label=DOWNLOAD%20APK)](https://github.com/vybhvdev/flux/releases/latest)

> ⚠️ Enable *"Install from unknown sources"* in Android settings to sideload the APK.

---

## 🎮 How to Play

1. You start with a **5×5 grid** — some cells ON (glowing), some OFF (dark)
2. Tap any cell to **toggle it and its 4 neighbors** (up, down, left, right)
3. Goal: get **every single cell to OFF**
4. Every puzzle is **guaranteed solvable** — no dead ends, no luck required

---

## ✨ Features

| Feature | Details |
|---|---|
| 🟡 **Neon visual design** | Dark background with glowing yellow cells and pink accents |
| 🎯 **3 difficulty levels** | Easy (5 scramble moves) · Medium (10) · Hard (18) |
| ⏱️ **Live timer** | Track how fast you can solve it |
| 🔢 **Move counter** | Optimize your solution |
| 💡 **Hint system** | Get a nudge when you're stuck |
| 🔄 **Reset & New Puzzle** | Retry the same puzzle or generate a fresh one |
| 📵 **Offline** | Works without internet on both web and Android |

---

## 🧠 How Puzzles Are Generated

FLUX uses a **reverse-scramble** algorithm to guarantee every puzzle is solvable:

1. Start from a fully solved (all-OFF) grid
2. Randomly apply `N` toggle moves based on difficulty
3. The resulting state is your puzzle — always reversible, always fair

---

## 🎨 Visual Design

```
Background:  #0a0a0f  — deep void black
Cell ON:     #e8ff47  — neon yellow glow
Cell OFF:    #1a1a2e  — dark navy
Accent:      #ff3c6e  — hot pink / red
Fonts:       Bebas Neue (title) · Space Mono (UI)
```

---

## 🗂️ What's in This Repo

```
/
├── index.html          # Web version — open in any browser
├── README.md
└── Releases            # Android APK — see GitHub Releases tab
```

---

## 🛠️ Tech Stack

| Version | Stack |
|---|---|
| 🌐 Web | Vanilla HTML · CSS · JavaScript (zero dependencies) |
| 📱 Android | Java · Native Android Views · No WebView |

---

## 🚀 Run the Web Version Locally

```bash
git clone https://github.com/vybhvdev/flux.git
cd Flux
open index.html
```

---

## 🗺️ Roadmap

- [ ] Animations on cell toggle (pulse/ripple)
- [ ] Best time leaderboard (local storage)
- [ ] Sound effects & haptic feedback
- [ ] 6×6 and 7×7 grid modes
- [ ] Daily challenge puzzle
- [ ] Play Store release

---

## 📄 License

Free to use, modify, and distribute. No attribution required.

---

<p align="center">
  <b>Built entirely on Android. Puzzle-first. No ads. No fluff.</b><br/>
  <sub>Made with ⚡ by Vaibhav</sub>
</p>
