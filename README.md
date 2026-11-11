# LoopArcadeReviewer

Sir Eijay's Loop Arcade (C Edition) is a self-contained static HTML game.

## Deploy to Vercel

Import this repository into Vercel and deploy from the repository root. The
included `vercel.json` selects Vercel's **Other** framework preset, skips a
build step, and serves the project root. No dependencies or environment
variables are required.

The game is kept as the original HTML file; its Google Fonts stylesheet
continues to load from Google Fonts, with the original CSS fallback fonts when
that service is unavailable.
