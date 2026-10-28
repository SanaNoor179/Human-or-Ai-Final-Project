# HUMAN OR AI? — Vanilla HTML, CSS & JavaScript Conversion

This folder (`vanilla-version/`) is a 1:1 conversion of the existing **"HUMAN OR AI?"** experiment into pure, standard HTML, CSS, and vanilla JavaScript without React, Vite, TypeScript, or npm build steps.

## How to Open & Run
1. Double-click **`index.html`** in Windows Explorer (or open it directly in Chrome, Edge, Safari, or Firefox via `file://`).
2. No development server, terminal, Node.js, or compilation required.

## Converted Architecture
- **`index.html`**: Clean semantic HTML containing all 6 application views:
  1. **Home / Landing Page**: Hero banner and 3D circular orbit carousel.
  2. **The Test (Quiz)**: 15-round challenge with guess buttons, outcome banner reveal, cue explanations, creator context, and influence factor multi-select.
  3. **Image Library (Archive)**: 3D curved semi-circle gallery with continuous left-to-right drift, hover slowdown, drag rotation, click-to-zoom, and 3D card flip.
  4. **Results & Stats**: Accuracy score gauge, tier breakdown, human vs AI authorship bias diagnostic, and visual cue breakdown bars.
  5. **About**: Research methodology and study background.
  6. **Contact**: Inquiry submission form and research participation notes.
- **`css/styles.css`**: Standard CSS replicating the typography (Newsreader, Poppins), colors (`#F5F4EF`, `#111111`, `#777777`, `#2A4365`), responsive layout, cards, and animations.
- **`js/data.js`**: Contains all 15 challenge rounds, answers, explanations, and carousel destinations in plain JavaScript variables.
- **`js/carousel.js`**: 3D orbit carousel for the landing page with perspective, inertia drag, and continuous drift.
- **`js/gallery.js`**: 3D curved semi-circle image archive using CSS 3D transforms (CORS-free for `file://` usage).
- **`js/quiz.js`**: Quiz state management, scoring, factor tracking, and results matrix generator.
- **`js/app.js`**: Page routing, mobile navigation drawer, and contact form handler.
- **`images/`**: All original images preserved with relative paths.

## Original Project Protection
The original React/Vite source code remains untouched in `src/`, with all original files preserved.
