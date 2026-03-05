# Private preview workflow

The public site remains the root `index.html` (under construction).

A private draft of the full multipage lab website is in `preview/`:

- `preview/index.html`
- `preview/research.html`
- `preview/team.html`
- `preview/publications.html`
- `preview/contact.html`

## How to preview locally

From the repository root run:

```bash
python3 -m http.server 8000
```

Then open:

- Public under-construction page: `http://localhost:8000/`
- Private draft homepage: `http://localhost:8000/preview/`

## Publishing later

When ready to make the full site public, move/copy content from `preview/` into the root pages (or switch root `index.html` to the preview homepage).
