# JEE Saathi — Class 11 · JEE Main

A personal study app for JEE Main preparation (Class 11, PCM). Everything lives in one self-contained HTML file — no build step, no server, no account. Your data is stored in your browser's local storage.

## What's inside (Phase 1)

- **Dashboard** — exam countdown, syllabus covered %, chapters due for revision, today's study minutes vs target, and a daily to-do list.
- **Syllabus tracker** — all 43 Class 11 chapters across Physics, Chemistry and Maths, grouped by unit. Each chapter has a status (Not started → Learning → Revised → Mastered) and a 1–5 confidence rating.
- **Focus timer** — Pomodoro style (25 min default, adjustable). Pick a subject and chapter, and finished sessions are logged automatically.
- **Notes** — per-chapter notes with full-text search across every chapter.
- **Revision** — automatic spaced repetition at 1, 3, 7, 14 and 30 day gaps. Marking a chapter revised pushes it to the next gap.
- **Tests** — log mock tests (100 marks per subject, 300 total, JEE Main pattern) and track averages, best score and trends.
- **Progress** — weekly study minutes, subject coverage bars, chapter status distribution and test score trend.
- **Settings** — exam date, daily target, Pomodoro length, and JSON backup / restore.

## Run it

Open `index.html` in any modern browser. That's it.

Or serve it locally:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy on GitHub Pages

1. Push this repo to GitHub.
2. Repo → **Settings** → **Pages**.
3. Under *Build and deployment*, set **Source: Deploy from a branch**, **Branch: `main` / `root`**.
4. Save. Your app is live at `https://<username>.github.io/<repo>/` in a minute or two.

## Roadmap

- **Phase 2** — Class 12 syllabus (PCM), JEE Advanced level problems, formula flashcards.
- Phase 3 — question bank with difficulty tags and mistake log.

## Data & privacy

No backend, no analytics, no network calls. Everything stays in your browser. Use **Settings → Download backup** before clearing browser data or switching devices.
