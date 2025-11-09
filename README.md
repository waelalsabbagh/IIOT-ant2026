# IIOT-ant2026 Website

This repository contains a static website for the "Workshop on Securing the Industrial Internet of Things (IIoT) - ANT 2026".

What I added:
- `index.html` — cleaned, responsive homepage that uses Tailwind CSS CDN and the three chair images already present in the repo (Alsabbagh.png, Langendoerfer.jpg, Serpanos.jpg).
- `README.md` — this file with instructions to preview/publish.

How to preview locally:
1. Clone the repo:
   ```bash
   git clone https://github.com/waelalsabbagh/IIOT-ant2026.git
   cd IIOT-ant2026
   ```
2. Serve the folder with a simple static server (Python):
   ```bash
   python3 -m http.server 8000
   # then open http://localhost:8000 in your browser
   ```

Publish with GitHub Pages (recommended):
1. Go to the repository Settings -> Pages.
2. Under "Build and deployment", select "Branch: main" and folder "\(root)" then Save.
3. GitHub Pages will publish the site at `https://waelalsabbagh.github.io/IIOT-ant2026/` within a few minutes.

Notes:
- Images `Alsabbagh.png`, `Langendoerfer.jpg`, `Serpanos.jpg` are referenced relatively (e.g., `<img src="Alsabbagh.png">`) and must remain at the repository root alongside `index.html`.
- If you prefer the site served from `gh-pages` branch instead of `main`, let me know and I will create a `gh-pages` branch with the same files.

If you want, I can also:
- create a `gh-pages` branch and push these files there so the site is automatically published,
- add a favicon, contact form, or Google Analytics snippet,
- update Workshop-Ant2026.html to redirect to `index.html` or remove duplication.
