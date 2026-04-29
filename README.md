# HTML Slides (Public)

Self-contained HTML presentation slides hosted via **GitHub Pages**. Each subdirectory contains one talk — a single `index.html` with all assets (images, fonts) Base64-embedded.

| Directory | Talk | Date |
|---|---|---|
| `cms_tb_meeting_es_2026/` | BTL Time Resolution from Energy Sharing Events (TB Meeting) | Apr 24, 2026 |
| `hig25006_preapproval/` | HIG-25-006 BSM H→ττ Pre-approval (98 slides) | Apr 27, 2026 |
| `Hfrontend-slides-PKU-skin/` | 9 Skin Showcase Previews (classic, bold, cobalt, voltage, botanical, jade, lavender, cyber, terminal) | Apr 29, 2026 |
| `frontend_slides_intro/` | Frontend Slides PKU — Technical Tutorial (18 slides, voltage skin) | Apr 29, 2026 |

## Access

All slides are served via GitHub Pages at:

```
https://ky230.github.io/Html-slides-public/<subdir>/index.html
```

For example:
- [cms_tb_meeting_es_2026](https://ky230.github.io/Html-slides-public/cms_tb_meeting_es_2026/index.html)
- [hig25006_preapproval](https://ky230.github.io/Html-slides-public/hig25006_preapproval/index.html)
- [frontend_slides_intro](https://ky230.github.io/Html-slides-public/frontend_slides_intro/index.html)

### Skin Previews

| Skin | Preview Link |
|------|-------------|
| 🏛️ classic | [Preview](https://ky230.github.io/Html-slides-public/Hfrontend-slides-PKU-skin/classic/index.html) |
| 🔥 bold | [Preview](https://ky230.github.io/Html-slides-public/Hfrontend-slides-PKU-skin/bold/index.html) |
| 💎 cobalt | [Preview](https://ky230.github.io/Html-slides-public/Hfrontend-slides-PKU-skin/cobalt/index.html) |
| ⚡ voltage | [Preview](https://ky230.github.io/Html-slides-public/Hfrontend-slides-PKU-skin/voltage/index.html) |
| 🌿 botanical | [Preview](https://ky230.github.io/Html-slides-public/Hfrontend-slides-PKU-skin/botanical/index.html) |
| 🍀 jade | [Preview](https://ky230.github.io/Html-slides-public/Hfrontend-slides-PKU-skin/jade/index.html) |
| 💜 lavender | [Preview](https://ky230.github.io/Html-slides-public/Hfrontend-slides-PKU-skin/lavender/index.html) |
| 🌐 cyber | [Preview](https://ky230.github.io/Html-slides-public/Hfrontend-slides-PKU-skin/cyber/index.html) |
| 💻 terminal | [Preview](https://ky230.github.io/Html-slides-public/Hfrontend-slides-PKU-skin/terminal/index.html) |

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
