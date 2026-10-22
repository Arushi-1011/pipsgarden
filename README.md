# Pip's Little Garden 🌷🐰

A small, free browser game made with plain HTML, CSS, and JavaScript. No build tools, dependencies, external assets, or paid services are required.

## Play locally

1. Download or unzip the project.
2. Open `index.html` in a modern browser.
3. Click **Start gardening**.

## Controls

- Move: Arrow keys or WASD (on mobile, use the directional buttons)
- Pause / resume: Space or Escape
- Toggle sound: M, or click the sound indicator in the bottom-right corner

## Goal

Collect flowers for points, pick up golden blooms for bonus points, and dodge the speedy little beetles. You have three hearts and 90 seconds. Beetles are slower, and a collision briefly knocks the beetle away to give Pip room to recover. Reach 120 points to complete the garden goal, but the round keeps going so you can enjoy the remaining time. The game ends when all three hearts are lost or the 90-second timer runs out; if you reached 120 points by then, you earn the Garden Superstar win screen. Your best score is saved locally in your browser.

## Publish for free with GitHub Pages

1. Create a public repository on GitHub.
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under the build/deployment section, choose **Deploy from a branch**, select `main` and `/(root)`, then save.
5. Once deployment finishes, GitHub will show your game's public URL in the Pages settings.

The canvas automatically renders at your screen pixel density for sharper graphics on Retina/high-DPI displays. The game runs entirely in the browser and uses locally generated shapes and Web Audio tones—there are no external assets or API calls.


The end screen celebrates a new personal best and displays a hand-drawn bouquet based on the flower types collected during that round. The round lasts 90 seconds. The canvas adapts to high-density/Retina displays for sharper rendering.
