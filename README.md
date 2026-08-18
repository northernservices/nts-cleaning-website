# Northern Clean by Northern Trusted Services

Single-page site for a cleaning service (Offices, Home, Commercial), built with
Tailwind CSS and Alpine.js via CDN — no build step required.

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000

## Deploy to GitHub Pages

1. Push this repo to GitHub.
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
4. Pick the `main` branch and `/ (root)` folder, then **Save**.
5. The site will be published at `https://<username>.github.io/<repo-name>/`.

## Notes

- The contact form does not send data anywhere yet — submitting it logs the
  `{ name, contact, inquiry }` payload as JSON to the browser console.
- Tailwind is loaded via the Play CDN
