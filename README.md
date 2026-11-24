# Syntasa Nova demo

A static site: no build step, no server code.

- `index.html`: the demo deck (cover, Path 1 Nova in one slide, Path 2 in-session personalisation, Path 3 AI agents at work)
- `syn-sports-live.html`: the Syn Sports in-session personalisation demo (also runs on its own)
- `img/`: product photos and the two looping videos the demo uses
- `.nojekyll`: tells GitHub Pages to serve the files as they are

## Publish on GitHub Pages
1. Create a repository and upload everything in this folder to its root (keep the `img` folder).
2. Settings → Pages → Build and deployment → Source: "Deploy from a branch", Branch: `main`, folder `/ (root)`. Save.
3. After a minute the site is live at `https://<your-user>.github.io/<repo>/`.
   The demo on its own: `https://<your-user>.github.io/<repo>/syn-sports-live.html`

Fonts load from Google Fonts, so the page needs an internet connection; everything else is in this folder.
Syn Sports, Alex and his journey are fictional.
