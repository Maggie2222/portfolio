# Maggie — Program & Experience Design

I turn complex programs into experiences people can actually engage with.

My work sits at the intersection of:

- Program Design
- Learning Experience
- Project Management
- Interaction Design
- International Education

## Selected Work

### West Coast Innovation Practice
Designing a pre-trip and field-study experience around innovation.

### East Coast Leadership Journey
Connecting academic courses, field visits and reflection through a leadership narrative.

### Card-based Pre-trip Experience
A lightweight web experiment turning preparation into interaction.

### International Study Tour
Managing complex international programs from concept to delivery.

## Things I Build

Small experiments, prototypes and tools for making programs more engaging.

→ [Visit the portfolio](https://maggie2222.github.io/portfolio/)

---

## Structure

```
portfolio/
├── index.html              # single-page site
├── assets/
│   ├── css/style.css
│   └── img/                # project screenshots
└── README.md
```

## Run locally

Open `index.html` directly, or serve it:

```bash
python -m http.server 8000
# → http://localhost:8000
```

## Deploy to GitHub Pages

Repo: <https://github.com/Maggie2222/portfolio> — Pages is already enabled
(build type `legacy`, source `main` / `/ (root)`).

Site: <https://maggie2222.github.io/portfolio/>

Any push to `main` rebuilds automatically in 1–2 min.

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
- [ ] Add `projects/01–05.html` detail pages for Selected Work
- [ ] Give `[ experiments ]` a URL — currently inert, shows `[ soon ]`

---

Open to opportunities in program design, learning experience, innovation and project management.
