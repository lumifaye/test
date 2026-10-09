# ✨ Little Universe

**A tiny, interactive particle playground made with plain HTML, CSS, and JavaScript.**

Little Universe turns your browser into a little pocket cosmos. Click to spark a burst of stardust, drag to nudge particles around, and change the rules of the universe while it runs.

## Try it

- **Live demo:** https://lumifaye.github.io/test/ *(available after GitHub Pages is enabled for this repository)*
- **Source:** [`index.html`](./index.html)

## Features

- 🌌 Animated starfield and a soft, layered cosmic background
- 💥 Click or tap anywhere to create a particle burst
- 🖱️ Drag through the scene to stir up more stardust
- 🪐 **Four particle styles:** Gravity Well, Orbiting, Fireworks, and Free Drift
- 🎨 **Four color moods:** Cosmic Violet, Deep Ocean, Solar Flare, and Moonlight
- ⚡ Adjustable particle energy
- ⏯️ Pause and resume the animation
- ♻️ Remix the universe or clear the canvas
- 📱 Responsive layout with pointer and touch input
- ♿ Honors reduced-motion preferences for interface transitions

## Controls

| Action | How |
| --- | --- |
| Create a burst | Click or tap the canvas |
| Stir up particles | Click and drag |
| Pause / resume | Space bar or Pause button |
| Create a new arrangement | Press **R** or choose **Remix universe** |
| Clear particles | Escape or choose **Clear** |
| Change the feel | Use the Particle Style, Energy, and Color Mood controls |

## Run locally

No build step, package manager, server, or external library is required.

1. Download or clone this repository.
2. Open `index.html` in a modern browser.

For example:

```bash
git clone https://github.com/lumifaye/test.git
cd test
```

Then open `index.html` in Chrome, Firefox, Edge, or another modern browser. It should also work on a Chromebook in the browser, without Linux or the Play Store.

## Publish with GitHub Pages

1. Open the repository's **Settings**.
2. Select **Pages**.
3. Under the build/deployment source, choose **Deploy from a branch**.
4. Select the `main` branch and the `/ (root)` folder, then save.
5. Wait for the Pages deployment to finish. The live demo link above should then become available.

## Technology

- HTML5 Canvas for the particles and starfield
- CSS for the responsive glassy interface and cosmic styling
- Vanilla JavaScript for animation, pointer interactions, and controls

Everything lives in one HTML file. There are no dependencies, tracking scripts, accounts, or network requests required by the page itself.

## Project structure

```text
.
├── index.html   # The complete interactive experience
└── README.md    # Project guide
```

## License

No license has been specified yet. Until one is added, assume the usual default copyright applies and reuse is not automatically granted.
