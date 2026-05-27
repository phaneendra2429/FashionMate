# FashionMate Static Website

This is a standalone static website for explaining FashionMate's current working features.
It intentionally lives outside the mobile app folder so website files do not mix with the
React Native app. The current design is reference-inspired and uses hosted fashion imagery,
because there were no reusable local website image assets in the app.

## Open locally

Open `index.html` in a browser, or serve the folder with any static file server.

```bash
python -m http.server 8080
```

Then visit `http://localhost:8080`.

## Files

- `index.html` - page content and sections.
- `styles.css` - responsive visual design using FashionMate's current aura palette.
- `script.js` - small header scroll state enhancement.
