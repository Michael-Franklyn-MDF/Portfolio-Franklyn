# Portfolio-Franklyn

A clean, minimal personal portfolio showcasing my projects and skills as a developer based in Nairobi.

**Live site:** [michael-franklyn-mdf.github.io/Portfolio-Franklyn](https://michael-franklyn-mdf.github.io/Portfolio-Franklyn)

---

## Overview

This is my personal developer portfolio, built as part of my transition from a Business IT diploma background into professional app development. The site features a dual light/dark mode, a coral/orange accent colour system, and smooth scroll interactions — all written in plain HTML, CSS, and JavaScript.

---

## Features

- Dual light/dark mode with system preference detection and localStorage persistence
- Fully responsive across mobile, tablet, and desktop
- Smooth scroll navigation with active link highlighting via Intersection Observer
- Animated hero headline with coral underline on page load
- Project cards with hover lift effect
- Scroll-triggered fade-in animations on all sections
- Keyboard accessible with visible focus rings
- No build tools or package manager dependencies

---

## Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 (semantic) |
| Styling | CSS3 (custom properties, Flexbox, Grid) |
| Scripting | Vanilla JavaScript (ES6+) |
| Fonts | Inter · Plus Jakarta Sans (Google Fonts) |
| Hosting | GitHub Pages |

---

## Folder Structure

```
Portfolio-Franklyn/
├── index.html
├── css/
│   ├── reset.css         # CSS reset / base normalisation
│   ├── tokens.css        # Design tokens (colours, type scale, spacing)
│   └── styles.css        # All layout and component styles
├── js/
│   └── main.js           # Theme toggle, scroll behaviour, animations
└── assets/
    └── projects/         # Project screenshots
```

---

## Projects Featured

| Project | Description | Stack |
|---|---|---|
| I-PIPES | Role-based ICT policy evaluation web app with multi-role dashboards | PHP, MySQL, HTML, CSS, JS |
| Coffee Haven | A simple yet elegant café website template with a homepage, detailed menu, and contact section — ideal for small businesses needing a clean, ready-to-use site | HTML, CSS, JS |
| To Do List | Minimalist to-do list for organising tasks and boosting productivity | HTML, CSS, JS |
| Akan Name Generator | Discover your Akan name based on the day you were born, celebrating Ghanaian naming traditions | HTML, CSS, JS |

---

## Running Locally

No build tools or package managers needed.

1. Clone the repo:
   ```bash
   git clone https://github.com/Michael-Franklyn-MDF/Portfolio-Franklyn.git
   ```

2. Open the project folder:
   ```bash
   cd Portfolio-Franklyn
   ```

3. Open `index.html` directly in your browser, or use a local dev server for auto-reload:
   ```bash
   # If you have VS Code / Cursor with Live Server installed:
   # Right-click index.html → "Open with Live Server"

   # Or with Python:
   python3 -m http.server 8000
   # Then visit http://localhost:8000
   ```

---

## Contact

**Michael Franklyn**
- GitHub: [@Michael-Franklyn-MDF](https://github.com/Michael-Franklyn-MDF)
- Email: michaeldavidfranklyn@gmail.com

---

© 2026 Michael Franklyn. Built from scratch.
