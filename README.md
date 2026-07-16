# merge-legion-2D- (GitHub Pages)

Public **GitHub Pages** host for **Merge Legion** — a Phaser 3 + TypeScript merge-battle browser game.

This repo holds only the built static site (`index.html` + `assets/`). It is **generated**, not edited by
hand: the game's source lives in [MergeLegion2D](https://github.com/ValeriiTsarov/MergeLegion2D), whose
`npm run deploy` produces a fresh production build and pushes the ready-made files here. This repo's
`.github/workflows/pages.yml` then publishes them.

**Play:** https://valeriitsarov.github.io/merge-legion-2D-/

> Settings → Pages → Source must be **"GitHub Actions"** (not "Deploy from a branch") for `pages.yml` to publish.
