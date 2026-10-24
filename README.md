# Morphic DevS — Website source

This is the latest 3D website source, including the original supplied logos.

## Open and run

1. Extract this ZIP.
2. Open the extracted `Morphic-DevS` folder in your editor (Antigravity).
3. Open `index.html` in a browser for a quick preview, or start a local static server from this folder:

   Windows: `py -m http.server 8000`
   macOS / Linux: `python3 -m http.server 8000`

4. Visit http://localhost:8000.

Python is needed only for the optional local server. There is no npm install or build step. An editor's static preview server also works.

## Files

- index.html — page structure, content, contact links, and original-logo placement
- style.css — responsive styles, themes, CSS 3D fallback and animations
- app.js — theme, navigation, concept dialogs and project brief actions
- scene.js — WebGL sculpture, draggable CSS 3D fallback, motion controls and scroll reveal
- assets/morphic-devs-logo.png — original combined logo
- assets/morphic-devs-symbol.png — original symbol-only logo

## Important details

- Instagram: https://www.instagram.com/amluvo_dev
- Email: amluvodev@gmail.com
- The form opens a mailto email draft; it does not send messages or use a backend. Visitors review and send from their email app. A downloadable text brief is also available.
- Portfolio concepts and figures are illustrative, not real client projects.
- Google Fonts needs an internet connection. System fonts are used when unavailable.
- WebGL renders the sculpture when supported; CSS 3D is the fallback. The fallback and pause control were browser-tested; the QA browser did not support WebGL.
- Reduced-motion preferences are respected.
- Original logo PNG files are unchanged; CSS frames their existing white margins.

## Continue editing

Ask your coding assistant to inspect these files and preserve the exact original logos, email address, Instagram link, mobile layouts, and working form behavior while making your requested changes.

## Deploy elsewhere

Upload index.html, style.css, app.js, scene.js and the assets directory together to any static website host. No ChatGPT-specific runtime is required. Existing hosting identity, Git history, and credentials are intentionally excluded.
