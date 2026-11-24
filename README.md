# GameModeON website

A responsive static website inspired by the supplied GameModeON design reference.

## Files
- `index.html` — page structure and content
- `style.css` — responsive neon gaming design
- `script.js` — mobile navigation and current year
- `assets/design-reference.png` — supplied visual reference (if included)

## Publish on GitHub Pages
1. Open the repository `gamemodeon-official.github.io`.
2. Upload `index.html`, `style.css`, and `script.js` to the repository root (same level as each other).
3. Commit the changes to the `main` branch.
4. In **Settings → Pages**, keep **Deploy from a branch**, choose `main` and `/(root)`, then Save.
5. Wait for the GitHub Pages deployment to finish.
6. Open `https://gamemodeon-official.github.io/`.

## Keep app-ads.txt working
Keep `app-ads.txt` as a separate file in the repository root, alongside `index.html`.
Its public URL should be:
`https://gamemodeon-official.github.io/app-ads.txt`

The file should contain the exact seller line shown in your AdMob account:
`google.com, pub-3249388379603650, DIRECT, f08c47fec0942fa0`

Do not put `app-ads.txt` inside an `assets` folder or inside the privacy-policy subfolder.

## Before publishing
- Check that the Google Play links and contact email are correct.
- Check the app-ads.txt URL in a browser and make sure it shows the seller line, not a 404 page.
- Keep the privacy policy page available at the linked URL.
