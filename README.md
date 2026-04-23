# 🕹️ Mankar Games

A retro-arcade game portal hosted on GitHub Pages. Play all games directly in your browser — no downloads, no installs.

🔗 **Live Site:** `https://<your-github-username>.github.io/mankar-games/`

---

## 📁 Folder Structure

```
mankar-games/
├── index.html              ← Main portal (game selection screen)
├── README.md
└── games/
    ├── tic-tac-toe/
    │   └── index.html      ← Your Tic Tac Toe game
    └── tetris/
        └── index.html      ← Your Tetris game
```

> Each game lives in its own folder under `games/`. Adding a new game = adding a new folder.

---

## 🚀 How to Set Up GitHub Pages

### 1. Create the Repository
1. Go to [github.com](https://github.com) and click **New repository**
2. Name it `mankar-games` (or anything you like)
3. Set it to **Public**
4. Click **Create repository**

### 2. Upload Your Files
Upload the files matching the folder structure above. You can do this via:
- **GitHub web UI** — drag and drop files directly
- **Git CLI:**
  ```bash
  git init
  git add .
  git commit -m "Initial commit — Mankar Games portal"
  git branch -M main
  git remote add origin https://github.com/<your-username>/mankar-games.git
  git push -u origin main
  ```

### 3. Enable GitHub Pages
1. In your repo, go to **Settings → Pages**
2. Under **Source**, select `Deploy from a branch`
3. Choose branch: `main`, folder: `/ (root)`
4. Click **Save**
5. Wait ~60 seconds, then visit:  
   `https://<your-username>.github.io/mankar-games/`

---

## ➕ Adding a New Game

1. Create a new folder inside `games/`:  
   `games/your-game-name/index.html`

2. In `index.html` (the portal), copy an existing `.card` block and update:
   - The `href` to point to your new game folder
   - The game name, description, badge, and thumb emoji/color

3. Commit and push — GitHub Pages auto-deploys!

---

## 🎮 Games

| Game | Players | Description |
|------|---------|-------------|
| Tic Tac Toe | 2 | Classic 3×3 X's and O's |
| Tetris | 1 | Stack blocks, clear lines, chase the high score |

---

Made with ♥ by Mankar Games
