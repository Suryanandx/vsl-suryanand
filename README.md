# Founding Engineer as a Service — VSL

Single-file video sales letter for **Suryanand Sunil's** founding-engineer retainer service.

> Live offer: one founding engineer, flat monthly retainer, ships your product end-to-end. Backend, frontend, cloud, AI.

## Stack

- **Pure HTML + CSS + vanilla JS** — no build step, no framework
- **Inter + Instrument Serif** via Google Fonts
- **Self-contained** — client logos inlined as base64 data URIs
- **Fully responsive** — breakpoints at 1100 / 1024 / 880 / 640 / 420 px

## Run locally

```bash
python3 -m http.server 8765
# open http://localhost:8765/index.html
```

Or just double-click `index.html` — it works as a static file.

## Sections

1. Hero (gradient + centered headline + VSL video)
2. Tech-stack marquee
3. Credibility bar (Ex-Google, Founding Engineer, HIPAA, ecom scale)
4. Stats row (8 yrs / 50+ products / 30% faster ETL / 3 max clients)
5. Cost-of-waiting agitation
6. "Is this for you?" yes/no columns
7. Origin story (personal letter)
8. Experience timeline (ARAXIS · Google · Axium · Arizon)
9. Case studies (6 real projects with metrics)
10. Industries served (AI · Healthcare · Ecom · SaaS)
11. Testimonials (6 reviews)
12. Mid-page walkthrough video
13. Bento deliverables (8 areas)
14. Offer value stack
15. Pricing toggle (Monthly / 6mo -10% / 12mo -20%)
16. Add-ons (Project Management · Priority Support · Architecture Audit)
17. Bonus stack (May-only signup bonuses)
18. 30-day timeline
19. Retainer-walkthrough video
20. Comparison table (collapses to mobile cards)
21. Risk-reversal guarantee
22. FAQ
23. Final CTA

## Customization

| What to change | Where |
| --- | --- |
| Video embeds | `videoMap` object in `<script>` at the bottom |
| Cal.com booking link | search for `cal.com/suryanand` |
| Pricing | `planData` object in the script + `.price-amt` defaults in HTML |
| Bonus deadline date | search for `May 31` |
| Replace base64 logos | swap `data:image/png;base64,...` back to `assets/logos/*.png` |

## License

All content © 2025 Suryanand Sunil. Source structure available for reference.
