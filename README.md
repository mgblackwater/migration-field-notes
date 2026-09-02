# Migration Field Notes

A small static site teaching legacy-system migration — the techniques, the failure patterns, and
the working rules — drawn from a real modernization engagement.

**Live pages:** `index.html` · `approach.html` · `lessons.html` · `techniques.html` · `resources.html`
Hand-built HTML + one shared stylesheet. No framework, no build step, no tracking.

## Preview locally

```
python -m http.server 8000
```

then open http://localhost:8000.

## Live site

**https://mgblackwater.github.io/migration-field-notes/** — GitHub Pages, deployed from `main`,
root. The repository was made public on 2026-09-02 to serve it.

## Content policy

The site is written to be publishable: **the stories are real; the names and the client's figures are not here.** No client,
product, institution, person, hostname, credential, or security finding from the source engagement
appears in these pages, and **none may be added**. Exact engagement metrics — feature counts,
check totals, batch outcomes — are excluded too; the pages use honest magnitudes instead. The engagement is described only as "a national
healthcare workforce survey system." An anonymity sweep (a list of identifying terms, with a negative
control proving the sweep can fail) ran clean before first publish — re-run the idea after any
substantial edit.

**License: not yet chosen.** Until one is added, default copyright applies (all rights reserved —
readable, not reusable). CC BY 4.0 is the usual choice for teaching content; add `LICENSE` when
decided.

## Editing

Each page is standalone HTML sharing `assets/style.css`. The style supports light and dark themes
automatically. Keep the voice: plain English, no internal shorthand, every claim either a real
measured number or clearly marked as judgement.
