# SQ Collegiate — Website Project

## Folder Structure
```
sq-collegiate/
├── index.html
├── css/
│   └── style.css
└── assets/
    └── images/
        └── logo.png
```

## How to open in VS Code
1. Unzip this folder anywhere on your computer.
2. Open VS Code → File → Open Folder → select `sq-collegiate`.
3. Install the **Live Server** extension (if not already installed).
4. Right-click `index.html` → **Open with Live Server** to preview in the browser.

## Notes
- The logo has been cropped and cleaned up (transparent corners) and saved locally at `assets/images/logo.png`. Replace this file (keep the same name) any time you want to swap the logo.
- Hero, "Why Us", events, and blog photos are pulled live from Unsplash (CDN links) — no local download needed as long as there's an internet connection. If you'd rather have those saved locally too, drop your own images into `assets/images/` and update the `src` paths in `index.html`.
- All styling lives in `css/style.css` — colors are defined as CSS variables at the top (`--purple`, `--gold`, etc.) for easy theme changes.
