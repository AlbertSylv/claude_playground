# Claude Playground

A collection of small projects (games, videos, data visualizations, tools…) built with Claude.

- `index.html` — homepage listing every project
- `projects.js` — the project registry the homepage reads
- `projects/<slug>/` — one self-contained folder per project, entry point `index.html`

## Adding a project

1. Create `projects/<slug>/index.html` (plus any assets it needs).
2. Add an entry to `window.PROJECTS` in `projects.js`.

Everything is static — open `index.html` directly or host it with GitHub Pages.
