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

## Publication policy — read before making this repository public

The site is written to be publishable: **the numbers are real; the names are not here.** No client,
product, institution, person, hostname, credential, or security finding from the source engagement
appears in these pages, and none may be added. The engagement is described only as "a national
healthcare workforce survey system."

Before flipping the repository public:

1. Re-read every page against the rule above (`git grep -i` for anything that looks like a name).
2. Decide a content license (e.g. CC BY 4.0) and add it here.
3. Enable GitHub Pages (Settings → Pages → deploy from `main`, root). Note: on a free plan, Pages
   requires the repository to be public.

## Editing

Each page is standalone HTML sharing `assets/style.css`. The style supports light and dark themes
automatically. Keep the voice: plain English, no internal shorthand, every claim either a real
measured number or clearly marked as judgement.
