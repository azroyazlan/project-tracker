# Project Tracker

A simple project tracking web app in a single HTML file — no installation or server required.

## Features
- **Dashboard** — project & milestone counts, overdue list, per-milestone status table
- **Projects list** — each project shows milestone count, overall progress and overall status
- **Add / Edit screen** — a project contains **multiple timelines/milestones**, each with its own name, PIC, start & end date, status and progress %
- Project overall status & progress are computed automatically from its milestones
- Milestones past their end date are automatically flagged **Overdue**
- Data is saved in your browser (localStorage)

## How to run
Just open `index.html` in any browser. Or serve it locally:

```
npx serve .
```

## Deploy free on GitHub Pages
1. Push this repo to GitHub
2. Repo → Settings → Pages → Source: `main` branch, `/ (root)`
3. Your app will be live at `https://<your-username>.github.io/<repo-name>/`
