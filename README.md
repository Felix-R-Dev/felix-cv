# felix-cv

A modern, responsive CV web page for a software developer — built with plain HTML and CSS, following 2026 best practices.

## Structure

```
felix-cv/
├── index.html   # Semantic CV markup
└── style.css    # Responsive, print-friendly styles
```

## Features

- **Semantic HTML5** — proper use of `<header>`, `<main>`, `<section>`, `<article>`, `<address>`, `<time>`
- **Fully responsive** — works on mobile, tablet, and desktop
- **Print-friendly** — dedicated `@media print` stylesheet with correct colours and page-break hints
- **Accessible** — ARIA labels, focus styles, sufficient colour contrast
- **No build step** — open `index.html` directly in any browser
- **Fast** — single CSS file, Google Fonts loaded asynchronously

## Getting started

Just open `index.html` in your browser — no server or build step required.

```bash
open index.html        # macOS
xdg-open index.html    # Linux
start index.html       # Windows
```
