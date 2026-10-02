# 👺 Goblin Hoard

A self-contained clicker/idle game. Poke Grub the Goblin, steal gold, buy upgrades, and recruit goblin minions for passive income. All progress auto-saves to local storage — no build step, no dependencies.

Built with vanilla HTML/CSS/JS, ready for GitHub Pages.

## Play

Live: **https://thekloakedsignal.github.io/goblin-hoard/**

## Features

- Click-to-loot with squish animation, floating gold particles, and idle bounce
- Six upgrade types: click-power boosts (dagger, boots, sack) and auto-income (minions, thieves' guild, dragon)
- localStorage save/load, autosave every 5 s, plus on exit
- Goblin quips and a Web Audio coin chime (mutable)
- Fully self-contained single `index.html` — no toolchain

## Deploy to GitHub Pages

1. Create a **new** repo named `goblin-hoard` (do not initialize or add any files)
2. Commit `index.html` (and this `README.md`) to `main`
3. In the repo: **Settings → Pages → Source → Deploy from a branch → main / (root) → Save**
4. Within a minute the site is live at `https://<username>.github.io/goblin-hoard/`

## Reset a save

Click the **Reset hoard** button in the footer, or clear `localStorage` key `goblin-hoard-save-v1`.