# Go Programming: The Master-Class Guide

An interactive single-page documentation guide covering Go programming from fundamentals to production engineering.

**Live site:** https://azhar25git.github.io/golang-tutorial-docs/

## Features

- 13 modules across 4 parts: Beginner → Intermediate → Advanced → Build Production
- 52 topics, each with conceptual explanation, idiomatic code example, and common anti-patterns
- Collapsible sidebar navigation with search/filter
- Syntax-highlighted code blocks (Prism.js)
- Dark/light theme toggle
- Progressive Web App ready — fully client-side, no server required

## Tech Stack

No build tools, no bundlers. Just static HTML, CSS, and JavaScript.

- [Alpine.js](https://alpinejs.dev/) — reactive UI
- [marked](https://marked.js.org/) — markdown rendering
- [Prism.js](https://prismjs.com/) — syntax highlighting

## Project Structure

```
├── index.html      # HTML shell
├── style.css       # All styles
├── app.js          # All logic (nav data, content, routing, theme)
└── README.md
```

All documentation content is stored as base64-encoded markdown directly in `app.js` — no external files needed.

## License

MIT

Open `http://localhost:8000` in your browser.

## Project Structure

```
├── index.html      # HTML shell
├── style.css       # All styles
├── app.js          # All logic (nav data, content, routing, theme)
└── README.md
```

All documentation content is stored as base64-encoded markdown directly in `app.js` — no external files needed.

## License

MIT
