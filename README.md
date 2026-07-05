# Algo Veil Technologies

The marketing site for **Algo Veil Technologies, LLC** — an independent software engineering and AI/ML architecture practice.

- Live: <https://algoveil.tech/>
- Contact: <hello@algoveil.tech>

## Stack

Plain HTML/CSS/JS. No build step. Deployed static from this repo.

- **Fonts** — Fraunces variable (SIL Open Font License) via Google Fonts
- **Motion** — Lenis smooth scroll (MIT) via CDN, lazy-loaded on idle
- **Imagery** — Unsplash CDN for stock, `raw.githubusercontent.com` for portfolio screenshots
- **Icons** — inline SVG only

## Pages

| Path | Purpose |
|---|---|
| `/` | Landing page (hero, disciplines, work, impact, engagement principle, insights, about, contact) |
| `/insights.html` | Insights index — long-form technical articles |
| `/insights/rag-faithfulness.html` | First published article — RAG citation-faithfulness harness |
| `/work/cadence.html` | Case study — real-time voice AI pipeline pattern |
| `/work/acuity.html` | Case study — hybrid-retrieval RAG (open-source reference implementation) |
| `/work/bastion.html` | Case study — multi-provider LLM gateway (open-source reference implementation) |
| `/work/sentinel.html` | Case study — forensic interview analysis platform |
| `/privacy.html` `/terms.html` `/cookies.html` | Legal |
| `/404.html` | Brand-consistent 404 |

## Local preview

```bash
python3 -m http.server 8080
# then open http://127.0.0.1:8080/
```

## Deployment

Deployed to Vercel from the `main` branch. Any push updates the production site within ~30 seconds. Preview deployments are created for pull requests automatically.

## License

All content and code in this repository is © Algo Veil Technologies, LLC.
Third-party licenses honored:
- Fraunces: SIL Open Font License
- Lenis: MIT
- Unsplash imagery: Unsplash License
