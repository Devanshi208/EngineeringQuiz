# Which Engineering Field Are You?

A 20-question quiz that matches you to the engineering field that actually fits — Mechanical, Electrical, Computer Science, Robotics, Cybersecurity, AI, and 9 more. Built as a single self-contained HTML file: no backend, no API keys, no build step.

**Live demo:** _add your deployed link here_

## Features
- 20 questions per attempt, pulled from a rotating bank of 36 — retake it and get a genuinely different set (up to 3 unique rotations, then a shuffled mix)
- Deterministic scoring — same answers always produce the same result
- Full results breakdown across all 15 fields, plus career paths and future outlook for your top match
- Zero dependencies beyond Google Fonts

## Run it locally
Just open `index.html` in any browser. That's the whole app.

```bash
git clone https://github.com/YOUR-USERNAME/engineering-quiz.git
cd engineering-quiz
open index.html   # or double-click it
```

## Deploy it

**GitHub Pages**
1. Push this repo to GitHub
2. Go to Settings → Pages
3. Set source to the `main` branch, root folder
4. Your quiz is live at `https://YOUR-USERNAME.github.io/engineering-quiz`

**Vercel**
1. Go to [vercel.com/new](https://vercel.com/new)
2. Import this GitHub repo
3. Leave all build settings blank (it's static HTML — no framework, no build command)
4. Deploy — you'll get a `.vercel.app` URL instantly, with a custom domain option later

## Tech
Vanilla HTML, CSS, and JavaScript. No React, no npm, no API keys — everything runs client-side in the browser.
