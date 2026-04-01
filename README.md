# UTAK SAT 2026 — Booth Tools

Two tools for the SAT 2026 conference booth, hosted as a static site on Render.

## Pages

- `/` — Booth lead intake form (PIN-protected lead review)
- `/cheatsheet` — Product Q&A field reference

## Deploying on Render

1. Push this repo to GitHub
2. Go to [render.com](https://render.com) → New → Static Site
3. Connect your GitHub repo
4. Render will auto-detect `render.yaml` and deploy

## Notes

- Lead data saves to browser localStorage on the iPad
- Export CSV from the lead review screen at the end of each day as a backup
- PIN for lead review: stored in `index.html`
- QR codes require internet/wifi to load
