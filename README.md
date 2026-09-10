# Portfolio

Minimal monospace portfolio — Program · Experience · Design.

## Structure

```
portfolio/
├── index.html              # single-page site
├── assets/css/style.css
├── projects/               # one page per Selected Work item
│   ├── 01.html … 05.html
└── README.md
```

## Run locally

Open `index.html` directly, or serve it:

```bash
python -m http.server 8000
# → http://localhost:8000
```

## Deploy to GitHub Pages

1. Create repo `maggie2222/portfolio` and push to `main`.
2. Settings → Pages → Build and deployment
3. Source: **Deploy from a branch** → Branch `main` / folder `/ (root)`
4. Wait 1–2 min → `https://maggie2222.github.io/portfolio/`

## Design tokens

All in `:root` of `assets/css/style.css`.

| Token     | Value    | Use              |
|-----------|----------|------------------|
| `--fg`    | `#111`   | body text        |
| `--muted` | `#8a8a8a`| labels, numbers  |
| `--line`  | `#dcdcdc`| rules, dashes    |
| `--measure` | `640px`| content width    |

## Add a screenshot

Drop a PNG into `assets/img/` with the exact filename — it replaces the dashed
placeholder automatically, no HTML edit needed.

| Group           | Sub-item              | Filename                            |
|-----------------|-----------------------|-------------------------------------|
| media research  | 美西                  | `assets/img/media-west.png`         |
| media research  | 美东                  | `assets/img/media-east.png`         |
| card Draw       | 美西                  | `assets/img/card-draw-west.png`     |
| card Draw       | 美东                  | `assets/img/card-draw-east.png`     |
| Program maps    | Future Decision Map   | `assets/img/program-decision.png`   |
| Program maps    | 美西课程脉络          | `assets/img/program-west.png`       |
| experiments     | (留空)                | `assets/img/experiments.png`        |

Recommended size: 1280 × 800 (16:10).

## Before going live

- [ ] Replace `mailto:hello@example.com` with real email
- [ ] Point `[ Resume ]` at a real PDF
- [ ] Update `projects/*.html` links once detail pages exist
- [ ] Give `[ experiments ]` a URL — currently inert, shows `[ soon ]`
