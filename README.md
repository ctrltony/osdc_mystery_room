# OSDC Mystery Room

## Case #001 — The Missing Commit

A fictional detective and investigation website for the Open Source Developers Club. It follows a suspicious commit in the fictional `OSDC/Project-X` repository and lets visitors review a case file, suspects, repository history, evidence, logs, clues, and a final report form.

## Technologies

- HTML5
- CSS3

**Current version:** HTML + CSS only. No JavaScript, frameworks, backend, database, or APIs are used.

## Pages

- `index.html` — cinematic case entry point
- `case.html` — incident report and timeline
- `suspects.html` — contributor access records and statements
- `repository.html` — reconstructed repository snapshot
- `evidence.html` — evidence cards
- `terminal.html` — visual-only system log
- `clues.html` — responsive investigation wall
- `investigation.html` — final HTML form

## Structure

```text
.
├── css/style.css
├── images/               # local SVG avatar placeholders
├── index.html
├── case.html
├── suspects.html
├── repository.html
├── evidence.html
├── terminal.html
├── clues.html
└── investigation.html
```

## Future possibilities

- JavaScript interactions
- Evidence tracking
- Investigation scoring
- Multiple cases

The markup uses clear semantic sections, IDs, and reusable CSS classes so these enhancements can be added later without redesigning the site.
