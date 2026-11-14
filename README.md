# Image Prompting Guide

A four-part, self-contained HTML guide to prompting AI image models — foundations,
settings and controls, advanced character work, and real-world genre prompts. No
framework, no build step: every page is a standalone `.html` file that opens
directly in a browser.

## Pages

| File | Part | Focus |
| --- | --- | --- |
| `index.html` | — | Landing page linking the four parts |
| `prompting-guide-part1.html` | I | Foundations — what a prompt is, prose vs tags, token limits, emphasis |
| `prompting-guide-part2.html` | II | Settings & controls — steps, guidance, seeds, strength, resolution |
| `prompting-guide-part3.html` | III | Advanced — style mixing, consistent characters, framing, panels |
| `prompting-guide-part4.html` | IV | Real world — portraits, scenes, fantasy, 3D characters, prompt architecture |

Each part carries the same fixed header bar so you can jump between 1 · 2 · 3 · 4.

## Preview locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

Static site — publish directory `.`, no build command.
