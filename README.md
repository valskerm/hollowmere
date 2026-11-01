# Hollowmere

A solo Dungeons & Dragons 5.5e (2024 rules) adventure crossed with a Stardew Valley–style town builder. Restore a ruined valley town, fight on a tactical grid, and uncover what sleeps beneath the mine.

Everything runs in a single `index.html` file with no build step and no server.

## Put it on GitHub Pages

1. Create a new **public** repository on GitHub.
2. Upload every file from this zip to the root of the repository: `index.html`, `README.md` and `.nojekyll`.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to “Deploy from a branch”, pick `main` and `/ (root)`, then **Save**.
5. After a minute or two the game is live at `https://<your-username>.github.io/<repository-name>/`.

To update the game later, upload the new `index.html` over the old one.

> Uploading `.nojekyll`: it starts with a dot, so some computers hide it. If you can’t see it, you can skip it; the game works without it.

## Saves

Progress saves automatically in the browser you play in. Use **Hero → Export save** to download a backup, and **Import save** to load it on another device or browser.

## What’s in the game

- **Characters:** Fighter, Rogue, Wizard and Cleric, levels 1–10, with 2024 species, backgrounds, origin feats, weapon mastery and spellcasting.
- **Combat:** an 8×8 grid with initiative, movement, opportunity attacks, line of sight, conditions, concentration and death saves.
- **Story:** three acts, from restoring the town to the siege and the Sleeper beneath the mine, with three endings.
- **Town:** an illustrated map, 10 buildings with upgrades to level 3, workers, farming, townsfolk relationships and a defense rating.
- **Side content:** weekly bounties, random raids on the town, magic items with attunement, and Mirela’s traveling magic wagon.

## Notes

- Fonts load from Google Fonts. Without an internet connection the game falls back to system fonts and still works.
- Token images you upload for your character are stored inside your save.
