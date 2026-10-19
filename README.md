# QTR Family Wealth — review copy

Static freeze of the QTR build, published for client review only.

- **Not the live site.** qtrfamily.com is untouched.
- **noindex + Disallow-all**, because this republishes the client's own copy and must not
  compete with their live site in search.
- Regenerate with `python3 tools/qtr/export-review.py` from the localember repo; source of
  truth is `qtr/dist/qtr/`, emitted by `tools/qtr/build-pages.py`.
- Forms are not wired: a static page has no backend and the lead destination is still an
  open decision. Phone and email links work.
- Internal notes are in `.github/TODO.md`, not in the published root. GitHub Pages
  runs Jekyll on this repo (no `.nojekyll`), so that dot-folder is not served.
  The notes are not linked from the nav, the footer, or the sitemap.
