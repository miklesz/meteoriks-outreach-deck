# Meteoriks outreach deck

A reusable presentation explaining what Meteoriks juroring looks like in practice and encouraging more scene people to consider taking part.

This is an early draft, not an official Meteoriks statement.

## View locally

The presentation loads `slides.md` in the browser, so it needs a small local web server:

```bash
python3 -m http.server 8000
```

Then open <http://127.0.0.1:8000/>.

Use the arrow keys to change slides. Press `P` to open presenter mode with notes.

## Edit

- Content and speaker notes: `slides.md`
- Visual style: `style.css`
- Remark launcher and settings: `index.html`

Slides are separated with `---`. Speaker notes follow `???`.

## Publish

The public version is served by GitHub Pages from the repository's default branch. A push to `main` updates the published deck automatically.
