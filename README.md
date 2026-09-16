# FD-VAD project page

Static project page for **FD-VAD: Semantic Endpoint Detection for Streaming Full-Duplex Speech**.

## Files

```text
.
├── index.html
├── styles.css
├── script.js
└── assets/
    ├── semantic_endpointing.png
    ├── fd_vad_architecture.png
    └── FD_VAD_ICASSP_2027.pdf
```

## Deploy on GitHub Pages

Because the repository is named `fd-vad.github.io`, place these files at the repository root and push to the default branch. In GitHub Pages settings, use **Deploy from a branch**, with the repository root (`/`) as the publishing folder.

If the existing code repository must remain at the root, an alternative is to place the website files in `docs/` and configure GitHub Pages to publish from `/docs`. If you do that, move `index.html`, `styles.css`, `script.js`, and `assets/` together so the relative links continue to work.

## Local preview

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.
