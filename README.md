# Dragon Web — 墨流し (Suminagashi)

An interactive ink-marbling (suminagashi) art piece: drag to set sumi ink flowing
over a detailed Chinese dragon. Built with Three.js (GPGPU "stable fluids").

## Files
- `index.html` — the whole site, self-contained (Three.js + fonts load from a CDN)
- `dragon.png` — the dragon illustration (public domain / CC0)
- `og.jpg` — social-share preview image

## Run it on your computer
It uses JavaScript modules, so it needs a tiny local server — opening `index.html`
straight from the file won't work. From inside this folder, run **one** of:

- **Python:** `python -m http.server 3000` → then open <http://localhost:3000>
- **Node:** `npx serve .` → open the link it prints

## Put it online (free)
Drag this whole folder onto **https://app.netlify.com/drop** — you'll get a live
public link in a few seconds. (Or connect it to Netlify/Vercel from a Git repo.)

## Controls
- **Drag** anywhere (mouse or finger) — paint ink
- **Palette pill** — pick an ink colour (or multicolour)
- **自動演出 / Auto** — auto-animation on/off
- **洗い流す / Wash** — dissolve the ink away

Fully touch-responsive — on phones and tablets it boots on a lighter simulation
grid so it stays smooth, and auto-tunes down further if a device can't keep up.

## Credits & licence
- Dragon artwork: *"Green Chinese dragon"* — **public domain (CC0)**, via Wikimedia Commons.
- Type: Noto Serif JP (Google Fonts). Engine: Three.js.
- Code: **MIT** — see [LICENSE](LICENSE).
