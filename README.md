# Maths Adventure 🦊

A colourful, reward-based maths game for a young learner practising **addition and
subtraction**. Everything lives in a single self-contained file — `index.html` — with
no build step, no server, no internet, no accounts, and no ads.

## How to run it

**On this computer**
- Just double-click `index.html`. It opens in your browser and works straight away.

**On a tablet or phone**
1. Get the file onto the device. Easiest options:
   - Email `index.html` to yourself and open the attachment, **or**
   - Put it in a cloud folder (OneDrive/Google Drive) and open it from there, **or**
   - Serve it from this PC on your home Wi-Fi (see below) and open the address in the
     tablet's browser.
2. Once it's open, use the browser's **"Add to Home Screen"** option. It then launches
   full-screen like a real app, and remembers her progress.

**Serve it over home Wi-Fi (optional)**
If you have Python installed, from this folder run:
```
python -m http.server 8000
```
Then on the tablet (same Wi-Fi) open `http://<your-PC-IP>:8000`.

## What it does
- **Starts easy** (sums within 5–10) and **gently gets harder** (up to 20) when she's on
  a roll; **eases back** if she gets a few wrong in a row.
- **Big tappable buttons** (multiple choice — no typing answers).
- **Instant feedback**: happy sound + animation for correct; a gentle "good try" for
  wrong, then it **shows the right answer** so she's never stuck.
- **Counting dots** appear on easier questions as a visual aid.
- **Rewards**: coins 🪙, stars ⭐, a **pet that grows** (egg → dragon 🐉), a **sticker
  book** 📖, a **treasure progress bar** 🏆, and streak encouragement ("3 in a row! 🔥").
- **Personalised**: she types her name and the game cheers her on by name.
- **Saves automatically** between sessions (browser local storage).

## For grown-ups
Tap the **⚙️** button in the game for a progress summary (accuracy, best streak, current
level), to change the name, or to reset all progress.

> Progress is stored per-browser on the device. Using "Add to Home Screen" and the same
> browser keeps everything saved.
