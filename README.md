# Phlex Landing Page

Simple static landing page for Phlex Technologies.

## Local preview

Open `index.html` directly in your browser, or serve the folder with:

```powershell
python -m http.server 3000
```

Then visit `http://localhost:3000`.

## Cloudflare Pages

This project is a static site with a top-level `index.html`, so it can be deployed directly from Git.

Suggested Cloudflare Pages settings:

- Framework preset: `None`
- Production branch: `main`
- Build command: `exit 0`
- Build output directory: `/`
