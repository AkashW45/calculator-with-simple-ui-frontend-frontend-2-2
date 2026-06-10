# Calculator

A simple, client-side calculator application built as a single HTML file.

## Architecture

- **UI**: Single HTML file embedding CSS and JavaScript.
- **Logic**: All arithmetic operations performed client-side (JavaScript) — no backend required.

## Decisions (ADRs)

- **ADR-001**: Client-side arithmetic processing — all calculations happen in the browser.
- **ADR-002**: Single-file user interface — the entire UI is contained in `index.html`.

## Getting Started

Serve the file with any static file server. For example:

```bash
# Using npx (no install needed)
npx http-server . -p 8080 -o
```

Or open `index.html` directly in a browser (some features may require a server).

## Usage

- Click number buttons (0-9) and decimal point to enter values.
- Click operator buttons (+, −, ×, ÷) to select an operation.
- Click = to compute the result.
- Click C to clear the current input.

## Project Files

- `index.html` — The entire application.
- `package.json` — (optional) Start script for convenience.
- `.gitignore` — Standard ignores.
