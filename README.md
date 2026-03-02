# FLUX — Lights Out Puzzle 🟡

A sleek, browser-based **Lights Out** puzzle game built with pure HTML, CSS, and JavaScript. No dependencies, no build steps — just open and play.

## 🎮 How to Play

Click any cell on the 5×5 grid to toggle it **and its neighbors** (up, down, left, right) on or off.

**Goal:** Turn ALL lights OFF to solve the puzzle.

It sounds simple — but it's trickier than it looks!

## ✨ Features

- 3 difficulty levels: **Easy**, **Medium**, **Hard**
- Move counter & live timer
- **Hint** button to highlight a suggested area
- **Reset** to retry the same puzzle
- Every puzzle is guaranteed solvable
- Fully responsive — works on desktop and mobile
- No install, no dependencies, no framework

## 🚀 Getting Started

### Play Locally

Just open the file in any browser:

```bash
open puzzle-game.html
```

### Deploy to GitHub Pages

1. Create a new GitHub repository
2. Add `puzzle-game.html` and rename it to `index.html`
3. Push to your repo:
   ```bash
   git init
   git add index.html README.md
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git push -u origin main
   ```
4. Go to **Settings → Pages → Source** and select `main` branch
5. Your game will be live at `https://YOUR_USERNAME.github.io/YOUR_REPO/`

## 🛠️ Customization

Everything is in a single HTML file — easy to tweak:

| What | Where |
|------|-------|
| Grid size | Change `SIZE` variable in the `<script>` |
| Difficulty (# of scramble moves) | Edit `difficultyMoves` object |
| Colors & theme | CSS variables at the top (`:root`) |
| Fonts | Google Fonts import in `<head>` |

## 📦 Tech Stack

- **HTML / CSS / JavaScript** — vanilla, no frameworks
- **Google Fonts** — Bebas Neue + Space Mono (SIL Open Font License)

## 📄 License

Free to use, modify, and distribute. No attribution required.
