# 200 YEARS OF GROWTH
### An Interactive Stock Market Terminal

> *"200 years of data. One conclusion: UP."*

A single-file, zero-dependency interactive web experience visualizing 200 years of stock market history from 1896 to the present day. Built with raw HTML, CSS, and JavaScript — no frameworks, no build tools, just open and run.

---

## LIVE DEMO

Open `market_unleashed.html` in any modern browser. That's it.

---

## FEATURES

**Scroll-Triggered Typewriting**
Every heading, section title, timeline entry, and closing statement starts completely blank. As you scroll each element into view, a blinking cursor appears and the text writes itself character by character at natural typing speed — complete with colored mid-word accents.

**Numbers From Zero**
All counters (DJIA, S&P 500, growth multiple, years undefeated) animate from `0` on page load with a smooth easing curve. Every stat card in the milestones table also counts up from zero the first time it enters the viewport.

**Live Market Feed**
20 stocks updating every 155ms with simulated price movements. Each card flashes green or red on every tick. Prices, percentage changes, and colors all update in real time.

**Dynamic Stats Table**
The entire milestones grid blinks on and off twice per cycle. Simultaneously, random cards twitch their values up or down — number, border glow, background, and progress bar all switch between green and red. Occasional spike events briefly enlarge the number for dramatic effect.

**Charts**
- Logarithmic DJIA line chart from 1896 to 2024 — crash events marked in red
- `$1,000 Invested` bar chart showing compound growth across different entry years
- 10-year rolling S&P 500 returns — green for positive decades, red for negative

**Visual Effects**
- Matrix rain background (green, red, white characters)
- CRT scanline overlay
- Glitch effect on the hero title
- Dual scrolling ticker tapes (top and bottom)
- Rotating quotes from Buffett, Graham, Templeton, Einstein
- Vertical timeline spanning 1896 to 2024

---

## TECH STACK

| Layer | What |
|---|---|
| Structure | Plain HTML5 |
| Styling | Vanilla CSS3 (animations, grid, clip-path) |
| Logic | Vanilla JavaScript (ES6+) |
| Charts | [Chart.js 4.4.1](https://cdnjs.cloudflare.com/ajax/libs/Chart.js/4.4.1/chart.umd.js) via CDN |
| Fonts | Bebas Neue · Orbitron · Share Tech Mono via Google Fonts |

No npm. No bundler. No framework. One file.

---

## GETTING STARTED

```bash
# Clone or download the repo
git clone https://github.com/yourname/200-years-of-growth.git

# Open in browser
open market_unleashed.html
# or just double-click the file
```

Requires an internet connection on first load for Google Fonts and Chart.js CDN. After that, works offline.

---

## FILE STRUCTURE

```
/
├── market_unleashed.html   ← entire app lives here
└── README.md
```

---

## TIMELINE COVERED

| Year | Event |
|---|---|
| 1896 | Dow Jones Industrial Average created — starts at 40 points |
| 1929 | Great Depression crash — DJIA: 381 → 41 |
| 1954 | Market reclaims 1929 highs — post-war boom |
| 1987 | Black Monday — largest single-day crash |
| 2000 | Dot-com peak — Nasdaq -78%, DJIA holds |
| 2008 | Global Financial Crisis — DJIA halved, then tripled |
| 2020 | COVID crash — fastest crash and fastest recovery in history |
| 2024 | All-time highs — DJIA 39,000+ |

---

## BROWSER SUPPORT

| Browser | Status |
|---|---|
| Chrome 90+ | ✅ Full support |
| Firefox 88+ | ✅ Full support |
| Safari 14+ | ✅ Full support |
| Edge 90+ | ✅ Full support |

---

## DISCLAIMER

> This project is for **educational and entertainment purposes only**.
> It is **not financial advice**.
> All market data shown is either historical or simulated.
> Past performance does not guarantee future results.
> The "live feed" is a simulation — prices are not real.

---

## LICENSE

MIT — do whatever you want with it.

---

*Built with: black, red, green, and white. Nothing else.*

