# SVG → CSS Converter

A **zero-dependency, single-file** web tool that converts any SVG into clean, production-ready CSS code — instantly, in your browser.

## Features

- **Drag & drop** SVG upload (or browse / paste directly)
- **4 output formats**
  - URL-encoded `background-image` (recommended — smallest, human-readable)
  - Base64 `background-image` (wider legacy compat)
  - `mask-image` / `-webkit-mask-image` (for icon masking & recolouring)
  - Inline `<img src="data:…">` HTML snippet
- **Live background preview** on dark, mid-tone, and light backgrounds
- **Conversion options** — minify, clean attributes, include `background-size`/`background-repeat`
- **Syntax-highlighted** output with one-click copy
- **SVG metadata** panel (dimensions, viewBox, file size)
- 100% client-side — your SVG never leaves your device

## Deployment (GitHub Pages)

1. Push this folder to a GitHub repository (or the `docs/` sub-folder of an existing one).
2. Go to **Settings → Pages** and set the source to the branch/folder containing `index.html`.
3. Done — GitHub Pages serves `index.html` automatically.

## Local preview

Just open `index.html` in any modern browser — no build step, no server required.

```
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

## License

MIT
