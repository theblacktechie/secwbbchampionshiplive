# SEC Women's Basketball Championship Dashboard
**Texas 78, South Carolina 61 · FINAL · March 8, 2026**

An interactive live game dashboard built for the 2026 SEC Women's Basketball Championship. Designed in the editorial style of The Athletic and Sportico: clean typography, tight data hierarchy, and zero clutter.

---

## What It Is

A single-file HTML application that tracked the championship game in real time and now serves as a permanent postgame record. It runs entirely in the browser with no backend, no database, and no build step.

---

## Features

### Live Score & Clock
- Countdown clock synced to game time with pause and resume controls
- Quarter-by-quarter score breakdown updated live
- Possession indicator and foul tracking

### Tabs
| Tab | What's Inside |
|---|---|
| **Score** | Live scoreboard, quarter grid, shooting splits, rebounding and turnover summary |
| **Stats** | Full shooting stats comparison (FG, 3PT, FT) with visual bar breakdowns |
| **Players** | Full roster for both teams with game stats and season averages |
| **Analysis** | Pre-game win probability model, final score card, analytics matchup bars, and typewriter-style postgame narrative |
| **Info** | Game details — date, venue, tip-off time, coaches, network |

### UPDATE Panel
Floating button that opens a live data entry panel for score, quarter, time, fouls, possession, and full shooting splits for both teams. Hitting **Apply** sets the clock running automatically.

---

## Tech Stack

- **React 18** (via CDN, no build required)
- **Babel Standalone** for JSX in-browser compilation
- **Inter** typeface via Google Fonts
- Fully responsive — mobile, tablet, and desktop layouts via CSS media queries

---

## How to Use

1. Open `sec-championship.html` in any modern browser
2. No installation or server needed — it runs locally
3. To update live data during a game, tap **✏ UPDATE**, enter current stats, and hit **Apply + Start Clock**
4. Use **⏸ PAUSE / ▶ RESUME** to stop and start the game clock

---

## Design Notes

- Color palette: SC Garnet `#73000A` · Texas Burnt Orange `#BF5700`
- Font: Inter (400–900 weight range)
- Square-cornered cards, cream-white background, minimal whitespace
- All text enforces single-line labels at the component level where appropriate
- Mobile: UPDATE panel becomes a full-width bottom sheet
- Desktop: content capped at 700px, centered

---

## File Structure

```
sec-championship.html   — complete app, self-contained
README.md               — this file
```

---

## Game Summary

Texas won its first SEC Women's Basketball Championship behind Justice Carlton's breakout performance (15 pts, 5 steals on 6-of-8 shooting) and 18 points from Madison Booker. The Longhorns blitzed South Carolina 27-12 in the first quarter and never relinquished control. Ta'Niya Latson was held to 4 points on 1-of-4 shooting. Joyce Edwards led SC with 13.

**Final: Texas 78, South Carolina 61**
