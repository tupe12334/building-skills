# Building Skills

A single-page slide deck ("Building Skills · Algorithm · Skill · LLM") built with plain HTML, CSS, and SVG — no build step, no dependencies.

**Live:** https://tupe12334.github.io/building-skills/

## Running locally

Open `index.html` directly in a browser, or serve the folder with any static file server, e.g.:

```bash
python3 -m http.server
```

## Navigation

- `→` / `↓` or the **Next** button: advance a slide
- `←` / `↑` or the **Prev** button: go back
- Swipe left/right on touch devices
- **Speak** button reads the current slide aloud using the browser's Web Speech API

## Deployment

Pushing to `main` triggers `.github/workflows/deploy.yml`, which publishes the repo root to GitHub Pages.

## Related Projects

- [moadim](https://moadim.io/) — loop engineering: build, schedule & run agent loops (from the same author).

## License

MIT — see [LICENSE](LICENSE).
