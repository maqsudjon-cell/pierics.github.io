# pierics · word game

A **Wordle clone** built from scratch with an IELTS academic vocabulary twist — guess the 5-letter word in 6 tries and learn definitions after each solve.

## Origin

This is a **Wordle clone** — the core gameplay (5-letter word, 6 guesses, green/amber/gray hints, emoji grid sharing) is directly inspired by [Wordle](https://www.nytimes.com/games/wordle/index.html) by Josh Wardle. The custom additions are:

- **IELTS/academic vocabulary** — 130+ answer words drawn from IELTS-relevant English, each with a definition and example sentence
- **Dual game modes** — Daily (same word for everyone) and Unlimited (play endlessly)
- **Dark theme** — custom pierics brand colors (mint green #3DDC91 on deep dark)
- **Zero dependencies** — single self-contained HTML file, vanilla JavaScript
- **Accessible** — full ARIA labels and screen reader support

## How to Play

Guess the hidden 5-letter word in **6 tries**.

| Color | Meaning |
|-------|---------|
| 🟩 Green | Correct letter, correct spot |
| 🟨 Amber | Correct letter, wrong spot |
| ⬛ Gray | Letter not in the word |

After each solve (or loss), the word's **IELTS definition** and example sentence are shown.

## Features

- **Daily mode** — same word for everyone each day (auto-rotates through the answer pool)
- **Unlimited mode** — random new word on every play
- **Stats tracking** — games played, win %, current/max streaks, guess distribution chart (stored in localStorage)
- **Emoji share** — copies a Wordle-style emoji grid to clipboard
- **Physical keyboard** — type on your keyboard; on-screen keyboard also works
- **Mobile-friendly** — responsive layout, touch-optimized, no double-tap zoom
- **Offline-ready** — single HTML file, no network needed after first load

## Tech Stack

- Single `.html` file
- Vanilla JavaScript (no frameworks, no build step)
- CSS Grid + custom properties
- localStorage for game state & stats
- ARIA for screen reader accessibility

## Deployment

This is a static HTML file — host it anywhere:

- **GitHub Pages** — push to a repo, enable Pages in Settings
- **Netlify / Vercel** — drag and drop `index.html`
- **Any static host** — serve the file, no server-side code needed

## License

MIT — do whatever you want with it.

---

*Gameplay mechanics inspired by [Wordle](https://www.nytimes.com/games/wordle/index.html). Vocabulary curated for IELTS test preparation.*
