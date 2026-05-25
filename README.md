# scratchpad

A running collection of one-off HTML documents — reports, plans, summaries, option comparisons — published via GitHub Pages so they can be shared with a link.

**Live site:** https://scolear.github.io/scratchpad/

## Conventions

- Each document is a self-contained HTML file in `docs/`
- Filenames: `YYYY-MM-DD-short-slug.html`
- Each doc inlines its own CSS so links don't rot
- `index.html` lists every doc, newest first — update it when you add a doc

## Adding a doc

1. Drop the HTML into `docs/` with the date-slug filename
2. Add a new `<li class="doc">` entry to `index.html` (at the top of the list)
3. `git add . && git commit -m "add: <slug>" && git push`
4. GitHub Pages rebuilds in ~30s; share the URL
