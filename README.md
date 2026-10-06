# REAP

Company website for REAP — an AI research and software development studio. Static site built with vanilla HTML, CSS, and JavaScript (no build step, no framework).

## Features

- Hero, About, Services, Tech Stack, Projects, Team, Careers, Testimonials, FAQ, and Contact sections
- Multi-language support (English / Español / বাংলা) via `i18n.js`
- Cmd+K command palette for quick navigation
- Animated hero terminal, scroll-reveal animations, cursor glow, tilt cards
- FAQ accordion, testimonials grid, expandable team bios
- Careers board with an email-based application flow (no backend required)
- One-click BibTeX citation copy on project cards

## Running locally

No build step — just serve the folder:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Structure

- `index.html` — all page markup
- `style.css` — all styles
- `app.js` — all interactive behavior
- `i18n.js` — translation strings and language switcher
- `assets/` — images
