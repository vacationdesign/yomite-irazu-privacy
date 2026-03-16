# CLAUDE.md

## Project Overview

This repository hosts the **privacy policy page** for **読み手いらず** (Yomite Irazu), an Android card-game reader app by Vacation design. It is a static, single-page website written in Japanese, served via GitHub Pages.

## Repository Structure

```
/
├── index.html   # Privacy policy page (Japanese, self-contained HTML with inline CSS)
├── README.md    # Brief project description
└── CLAUDE.md    # This file
```

## Key Details

- **Language**: The page content is entirely in Japanese. Preserve Japanese text accurately when editing.
- **Stack**: Plain HTML + inline CSS. No build tools, no JavaScript, no dependencies.
- **Hosting**: Designed for GitHub Pages (static file serving from the `main` branch root).
- **External references**: The page links to Google AI terms of service and includes a contact email.

## Development Workflow

- **No build step** — edit `index.html` directly.
- **No tests or linters** — verify changes by opening `index.html` in a browser.
- **Default branch**: `main`

## Conventions

- Keep all styling inline within the `<style>` block in `index.html`.
- Update the `最終更新日` (last updated date) in the page when making content changes.
- Maintain the existing section numbering (1–10) when adding or removing sections.
- Copyright line at the bottom should reflect the current year.
