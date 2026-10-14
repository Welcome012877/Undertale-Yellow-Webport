# Undertale Yellow — Webport

This repository hosts a web-port loader so you can play *Undertale Yellow* in your browser.

Play online (if GitHub Pages is enabled):

- https://Welcome012877.github.io/Undertale-Yellow-Webport/

What I did
- Replaced this repo's `index.html` with a working web-port loader that uses the genizy/web-port assets via jsDelivr.
- Added this README with a direct link and instructions.

If the game doesn't load
- Wait a minute after enabling Pages — GitHub Pages can take a short time to publish new content.
- Make sure Pages is enabled: Settings → Pages → Branch: `main` (root) → Save.
- If you prefer to host all assets in this repo (not via jsDelivr), copy the `undertale-yellow/` files (runner.wasm, runner.data, runner.js, game.unx.part*) into this repo and update `index.html` paths accordingly. Note: some files are large and may require Git LFS.

Play locally
1. Clone the repo: `git clone https://github.com/Welcome012877/Undertale-Yellow-Webport.git`
2. Serve locally: `cd Undertale-Yellow-Webport` then `python -m http.server 8000` (or use any static server)
3. Open `http://localhost:8000/` in your browser.

Credits and legal
- Loader and web-port files originally from [genizy/web-port](https://github.com/genizy/web-port/tree/main/undertale-yellow) and community contributors; I used the CDN-hosted assets so the repo stays small.
- Make sure you have the right to distribute any game data you host here. I am not responsible for copyrighted materials — host only what you're allowed to.

If you want, I can instead copy all web-port files into this repository (host locally) or enable GitHub Pages for you — tell me which and I'll proceed.
