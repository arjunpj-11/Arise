# ⚔️ ARISE — 60-Day Rise Challenge

A Solo Leveling-inspired personal productivity RPG that turns your daily routine into a quest log. Track habits, earn XP, level up through 50 ranks, and forge your limits over 60 days.

---

## ✨ Features

- **Daily Quest Log** — A time-locked routine with 16 structured tasks from 5 AM to 10 PM. Tasks unlock at their scheduled time and close if missed, keeping you honest.
- **Live Timers** — Duration-based quests (coding, deep work, exercise) have start/stop timers with 5-minute warnings and auto-complete.
- **XP & Leveling System** — 50 ranks across E → D → C → B → A → S tiers with a steep XP curve. Early levels are quick wins; S-Rank requires a real grind.
- **AI System Coach** — Powered by the Claude API. After logging effort, the System analyzes your input and delivers a Solo Leveling-style response with a concrete target for tomorrow.
- **Custom Skills** — Add your own habits with custom icons, XP values, and goals beyond the default routine.
- **Stats & Charts** — Daily XP bar chart (last 7 days), today's completion donut, and an XP-by-activity breakdown.
- **Streak Tracking** — Daily streak counter with best streak record.
- **60-Day Countdown** — Progress bar showing exactly where you are in the challenge with days remaining.
- **Light & Dark Mode** — Warm parchment light theme and deep charcoal dark theme, styled after the Imminiq design system. Persists across sessions.
- **Fully Offline** — Single HTML file, no build step, no dependencies beyond Chart.js (CDN). All data stored in `localStorage`.

---

## 🚀 Getting Started

No installation needed. Just open the file.

```bash
git clone https://github.com/your-username/arise-challenge.git
cd arise-challenge
open arise-imminiq-theme.html
```

Or simply download `arise-imminiq-theme.html` and open it in any modern browser.

---

## 🤖 AI Coach Setup

The AI coach uses the Anthropic Claude API. To enable it, you need to serve the file through a proxy that injects your API key, or modify the fetch call in the script to route through your own backend.

> The AI coach is optional — all other features work without it. If the API call fails, a fallback message is shown.

---

## 🗂️ File Structure

```
arise-challenge/
└── arise-imminiq-theme.html   # The entire app — single self-contained file
└── README.md
```

---

## 🎮 How It Works

1. Open the app each morning
2. Tasks unlock at their scheduled times — instant tasks (like Wake Up) have a 10-minute window; duration tasks require you to hit Start and run the timer
3. When a task completes, log what you did — the more specific, the better AI feedback you get
4. XP is added to your total, your rank updates, and your streak continues
5. Check the Records tab for charts and the Ranks tab to see how far you have to climb

---

## 🏆 Rank Progression

| Tier | Levels | XP Range |
|------|--------|----------|
| E-Rank | 1–5 | 100 – 450 XP per level |
| D-Rank | 6–10 | 600 – 2,000 XP |
| C-Rank | 11–20 | 2,800 – 29,000 XP |
| B-Rank | 21–30 | 37,000 – 235,000 XP |
| A-Rank | 31–40 | 285,000 – 1,350,000 XP |
| S-Rank | 41–49 | 1,600,000 – 6,100,000 XP |
| **Shadow Monarch** | **50** | **7,200,000 XP** |

---

## 🛠️ Built With

- Vanilla HTML, CSS, JavaScript — no framework
- [Chart.js](https://www.chartjs.org/) — for stats charts
- [Google Fonts](https://fonts.google.com/) — Playfair Display, DM Sans, DM Mono
- [Anthropic Claude API](https://www.anthropic.com/) — for the AI System coach
- Design inspired by [Solo Leveling](https://www.webtoons.com/en/action/solo-leveling/) and the Imminiq design system

---

## 📄 License

MIT — do whatever you want with it. Just rise.
