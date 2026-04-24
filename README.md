# HTML Slides (Public)

Self-contained HTML presentation slides hosted via **GitHub Pages**. Each subdirectory contains one talk — a single `index.html` with all assets (images, fonts) Base64-embedded.

| Directory | Talk | Date |
|---|---|---|
| `cms_tb_meeting_es_2026/` | BTL Time Resolution from Energy Sharing Events (TB Meeting) | Apr 24, 2026 |

## Access

All slides are served via GitHub Pages at:

```
https://ky230.github.io/Html-slides-public/<subdir>/index.html
```

For example:
- [cms_tb_meeting_es_2026](https://ky230.github.io/Html-slides-public/cms_tb_meeting_es_2026/index.html)

## How to Add a New Talk

1. Create a new directory under the repo root (e.g., `my_new_talk/`)
2. Place the **bundled** HTML file inside as `index.html`
3. Update the table above
4. Commit & push — GitHub Pages deploys automatically

```bash
mkdir my_new_talk
cp /path/to/presentation_bundle.html my_new_talk/index.html
git add my_new_talk/
git commit -m "feat: add my_new_talk slides"
git push
```

## Requirements

- Each `index.html` must be **fully self-contained** (all images Base64-embedded, CSS/JS inline)
- Use `bundle-html.py` from [frontend-slides-PKU](https://github.com/ky230/frontend-slides-PKU) to embed assets before uploading
- MathJax is loaded from CDN — internet connection required for LaTeX rendering

## Keyboard Shortcuts (in presentation)

| Key | Action |
|---|---|
| `↓` / `Space` / `PageDown` | Next slide |
| `↑` / `PageUp` | Previous slide |
| `G` | Go to slide (type number + Enter) |
| `F` | Toggle fullscreen |
