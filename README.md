# QTR Family Wealth — review copy

Static freeze of the QTR build, published for client review only.

- **Not the live site.** qtrfamily.com is untouched.
- **noindex + Disallow-all**, because this republishes the client's own copy and must not
  compete with their live site in search.
- Regenerate with `python3 tools/qtr/export-review.py` from the localember repo; source of
  truth is `qtr/dist/qtr/`, emitted by `tools/qtr/build-pages.py`.
- Forms are not wired: a static page has no backend and the lead destination is still an
  open decision. Phone and email links work.
- `TODO.md` is internal. It is not linked from the nav, the footer, or the sitemap.
