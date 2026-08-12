# Scoreboard

A lightweight, no-frills scoreboard app for keeping track of two teams' scores in real time. Built with plain HTML, CSS, and JavaScript — no frameworks, no build step.

**Live demo:** [tallyitup.netlify.app](https://tallyitup.netlify.app/)

## Features

- Two independent scoreboards (Team 1 / Team 2)
- Quick score adjustment buttons: `+1`, `+2`, `+3`, `-1`, `-2`, `-3`
- Clean, distraction-free interface — good for pickup games, trivia nights, or any head-to-head match you need to tally on the fly
- Custom display font for a scoreboard/arcade feel

## Getting Started

No build tools or dependencies required.

1. Clone the repo:
   ```bash
   git clone https://github.com/alikirat/scoreboard.git
   cd scoreboard
   ```
2. Open `index.html` in your browser.

That's it — the app runs entirely client-side.

## Usage

- Use the `+1` / `+2` / `+3` buttons to add points to a team's score.
- Use the `-1` / `-2` / `-3` buttons to subtract points (e.g. to correct a mistake).
- Each team's total updates instantly on screen.

## Project Structure

```
scoreboard/
├── index.html        # App markup
├── index.css          # Styling
├── index.js           # Score logic
├── cursed-timer.ttf    # Custom display font
└── .gitignore
```

## Deployment

The live version is deployed on [Netlify](https://www.netlify.com/). Any static host (Netlify, Vercel, GitHub Pages, etc.) will work since the app is fully static.

## License

No license specified yet — all rights reserved by default. Add a `LICENSE` file if you'd like to open this up for reuse.

## Author

**Ali Kirat**
- GitHub: [@alikirat](https://github.com/alikirat)
- Portfolio: [alikirat.netlify.app](https://alikirat.netlify.app)
