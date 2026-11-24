# product-nirvana

Product practice presentations by [finably.ca](https://finably.ca), published with GitHub Pages.

| Page | URL |
|---|---|
| Series hub | https://ben-finably.github.io/product-nirvana/ |
| Series 01 — Your product practice may need an overhaul | https://ben-finably.github.io/product-nirvana/series-01/ |
| Series 02 — 10X Agile | https://ben-finably.github.io/product-nirvana/series-02/ |

## Structure

```
product-nirvana/
├── index.html                 ← series hub (lists every deck)
├── series-01/index.html       ← canvas-animated deck
├── series-02/
│   ├── index.html             ← slide viewer (keyboard, click, swipe, #N deep links)
│   └── slides/001…099.webp    ← exact 1920×1080 renders of the master
└── masters/
    └── series-02/10X-Agile-finably_V3.pptx   ← MASTER (source of truth)
```

## Masters are the source of truth

`masters/series-02/10X-Agile-finably_V3.pptx` is the **master presentation**. Its design includes the author's
own hand edits and **must be preserved exactly as it is**: do not restyle, regenerate or "clean up" it or its
renders. To change Series 02, edit the master in PowerPoint, commit the new master, then re-render the slide
images from it.

Controls: → / Space / click right = next · ← / click left = previous · F = fullscreen · R = restart.
Add `#N` to a deck URL to open slide N directly.
