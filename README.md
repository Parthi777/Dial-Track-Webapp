# DialTrack Web App

Production-built Flutter Web bundle for the DialTrack admin dashboard, ready to deploy on Vercel as a static site.

## Deploy on Vercel

1. Import this repo on https://vercel.com/new
2. Framework preset: **Other**
3. Build command: leave blank
4. Output directory: `.` (root)
5. Click Deploy

The included `vercel.json` rewrites all routes to `index.html` so go_router deep links work.

## Local preview

```bash
python3 -m http.server 8080
# open http://localhost:8080
```
