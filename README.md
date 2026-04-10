# Mall Commerce Landing Page

Static HTML/CSS prototype for **Fynd Mall Commerce** — an omnichannel commerce platform for shopping malls. Built as a design preview for internal review before production implementation.

**Live preview:** https://vigneshasaithambi.github.io/mall-commerce-landing/solutions/mall-commerce/

## What is Mall Commerce?

A platform that lets mall operators create one digital storefront for their entire mall. Every tenant gets their own store on the mall's domain. Customers shop online and show up at the mall. Customers visit the mall and keep buying from home. One platform, one loop.

**Target audience:** Mall operators (Nexus, Phoenix, DLF, Lulu) and retail conglomerates (Reliance Retail, ABFRL, Tata).

## Page Structure (9 Folds)

| Fold | Section | Layout |
|------|---------|--------|
| 1 | Hero | 2-column (copy + dashboard mockup) |
| 2 | Run the whole mall from one screen | Bento grid (1 hero + 5 cards) |
| 3 | Online fills the mall | 3×2 card grid |
| 4 | The mall fills the cart | Zigzag (alternating rows) |
| 5 | Every tenant goes digital on day one | Header + 3×2 numbered grid |
| 6 | How it works | 4-step cards |
| 7 | Who is this for | 2 audience cards |
| 8 | CTA | Light band |
| 9 | FAQ | Accordion (9 items) |

## Tech Stack

- Static HTML + CSS (no framework, no JS)
- Inter font via Google Fonts
- Inline SVG icon sprites (no external image dependencies)
- Hosted on GitHub Pages

## Files

```
solutions/mall-commerce/
├── index.html          # Full page (9 folds)
├── styles.css          # All styles
├── requirements.md     # Content strategy + wireframe copy (from PDF)
└── assets/
    ├── hero-dashboard.svg   # Dashboard mockup for hero + bento
    ├── icons.svg            # Icon sprite (unused, inlined in HTML)
    └── logos.svg             # Logo sprite (unused, inlined in HTML)
```

## Local Preview

Open `solutions/mall-commerce/index.html` directly in a browser, or run a local server:

```bash
python3 -m http.server 8000
# then open http://localhost:8000/solutions/mall-commerce/
```

## Deployment

Hosted via GitHub Pages on the `main` branch. Any push to `main` auto-deploys within ~60 seconds.
