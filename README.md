# The Curriculum

Condensed degree-level courses, taught interactively, published with GitHub Pages.

**Site:** https://dantusjosh-png.github.io/curriculum/

## Layout

- `index.md` — course catalog + progress
- `how-it-works.md` — the pedagogical framework
- `courses/<slug>/index.md` — one landing page per course (sidebar section)
- `courses/<slug>/module-NN.md` — one page per module (nested in sidebar)
- `_templates/` — page templates used when adding courses/modules (not rendered)

Built with [Just the Docs](https://just-the-docs.com/) via `remote_theme` — GitHub Pages builds it automatically on push, no local tooling needed.
