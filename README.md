# pangea8 · word game

A Wordle-style word game with IELTS vocabulary trainer. Guess the 5-letter word in 6 tries.

## Features

- **Daily mode** — same word for everyone each day
- **Unlimited mode** — play as many games as you want
- **IELTS vocabulary** — learn definitions + example sentences after each solve
- **Stats** — track games played, win %, streaks, and guess distribution
- **Share** — copy emoji grid to clipboard
- **Keyboard & touch** — physical keyboard or on-screen keys
- **Accessible** — ARIA labels and screen-reader announcements
- **Zero dependencies** — single HTML file, vanilla JS
- **Dark theme** — pangea8 brand colors (mint green on deep dark)

## How to Play

- Guess the hidden 5-letter word in 6 tries
- 🟩 Green = correct letter, correct spot
- 🟨 Amber = correct letter, wrong spot
- ⬛ Gray = letter not in the word

## Deployment

This is a single static HTML file. Deploy anywhere:

### GitHub Pages
1. Push to a GitHub repo
2. Enable Pages in Settings → Pages → Deploy from `main` branch

### Netlify / Vercel
Drag and drop `index.html` onto their dashboard

### Any static host
Serve `index.html` — no build step, no server needed

## License

MIT
