# EyeGod · Trace Data OSINT

A multi-page static web app for OSINT research, styled with a dark glass UI.

## Stack

- Pure HTML / CSS / JavaScript — no build step required
- Fonts loaded from jsDelivr CDN (Inter, Montserrat, JetBrains Mono)

## Pages

| File | Purpose |
|------|---------|
| `index.html` | Landing / main search page |
| `login.html` | Sign-in page |
| `register.html` | Registration page |
| `dashboard.html` | User dashboard |
| `profile.html` | User profile & settings |
| `para_ia.html` | AI-assisted search |
| `docs.html` | Documentation |
| `faq.html` | FAQ |
| `privacy.html` | Privacy policy |
| `terms.html` | Terms of service |
| `logo.png` | Brand logo |

## Running locally on Replit

The configured workflow serves all files with Python's built-in HTTP server:

```
python3 -m http.server 5000
```

Open the preview pane — it will load `index.html` automatically.

## User preferences

- Keep the existing file structure (flat HTML files at root level)
- Dark theme — black background (`#000000`), off-white text (`#f0f0f0`)
