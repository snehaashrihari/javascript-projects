React demo for "Expanding Cards"

This folder contains a small Vite-based React app that reproduces the original Expanding Cards demo.


How to run (quick):
1. Open `day-1/react/index.html` in your browser. For best results, serve the folder over HTTP (some browsers block local imports).

Quick serve from the `react` folder:

```bash
# from workspace root
cd day-1/react
python3 -m http.server 8000
# then open http://localhost:8000 in your browser
Vite React project for "Expanding Cards"

Key files:
- `package.json` — scripts: `dev`, `build`, `preview`.
- `index.html` — Vite entry that loads `/src/main.jsx`.
- `src/main.jsx` — app entry (React + root render).
- `src/App.jsx` — the Expanding Cards component (same behavior as the original).
- `src/index.css` — styles copied from the original demo.

Quick start (from workspace root):

```bash
cd day-1/react
npm install
npm run dev
# open the printed local URL (usually http://localhost:5173)
```

How to use this for learning:
- `src/App.jsx` is a small functional component using `useState` to track which panel is expanded. Open and edit it to learn JSX, props, and hooks.
- Vite provides fast HMR so changes appear instantly in the browser.
