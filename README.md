# Know Your Boundaries — Scrut Design Quiz

A single-player quiz game for the Scrut design team to learn and practice the new Design–Product ownership model.

**18 scenario-based questions** with named characters (Neha, Arjun, Meera, Karan, Priya, Ravi, Sanya, Vikram) in realistic PM-Designer situations. Each player gets 12 randomized questions per game.

## How to Host on GitHub Pages (5 minutes)

### Step 1 — Create a GitHub repo

1. Go to [github.com/new](https://github.com/new)
2. Name it `design-quiz` (or anything you like)
3. Set it to **Public** (required for free GitHub Pages)
4. Click **Create repository**

### Step 2 — Upload the file

1. On the repo page, click **"uploading an existing file"** (or the **Add file → Upload files** button)
2. Drag and drop the **`index.html`** file from this folder
3. Click **Commit changes**

### Step 3 — Enable GitHub Pages

1. Go to **Settings** → **Pages** (left sidebar)
2. Under **Source**, select **Deploy from a branch**
3. Branch: **main**, folder: **/ (root)**
4. Click **Save**
5. Wait 1–2 minutes

### Step 4 — Share the link

Your game is now live at:

```
https://YOUR-USERNAME.github.io/design-quiz/
```

Send this link to your 4 teammates. Each person:
- Opens the link on their own device (phone or laptop)
- Enters their name
- Plays 12 questions solo
- Sees a shared leaderboard at the end (scores persist via browser storage)

## Note on Leaderboard

On GitHub Pages, the leaderboard uses `localStorage`, which means each device stores its own scores. If you want a truly shared leaderboard across devices, you'd need a backend (e.g., Firebase). For a 4-person team, the simplest approach: play during the same Google Meet call and screenshot/share your results.

## Files

- `index.html` — The complete game. Single file, no build step, no dependencies to install.
- `README.md` — This file.
