# SPEC.md — Zvonite Leshe (Звоните-Леше)

## Project
Landing page for a private appliance repair master ("Звоните-Леше").  
Target audience: homeowners in Moscow (Maryino, Bratyevo, Kapotnya, Brateyevo districts) needing oven or hob repair.

## Analytics
- **Yandex.Metrika** — counter ID: 110808907
  - webvisor: enabled
  - clickmap: enabled
  - ecommerce: dataLayer
  - accurateTrackBounce: enabled
  - trackLinks: enabled
  - SSR mode: enabled
  - Placed in `<head>` before closing `</head>`

## Structure
1. **navbar** — fixed-top glassmorphism navbar with logo, nav links, CTA phone button
2. **hero** — full-screen dark hero with master photo, headline, subtext, badges (Avito, experience, гарантия)
3. **services** — grid of repair services (oven, hob, induction, gas)
4. **why-us** — benefits section with icons (выезд, гарантия, запчасти, без посредников)
5. **how-it-works** — 4-step process (звонок → диагностика → ремонт → гарантия)
6. **reviews** — carousel of client testimonials
7. **faq** — accordion with common questions
8. **pricing** — price list table
9. **map** — location section with map placeholder
10. **footer** — contact info, social links, Avito link, copyright

## Styling
- **Palette**: dark navbar, white/light backgrounds, accent #0088cc (Telegram blue)
- **Typography**: Inter font family
- **Vibe**: trustworthy, professional, warm
- **Framework**: Bootstrap 5.3 (CDN) + custom CSS

## Responsive
- **Desktop**: full multi-column layouts
- **Tablet**: 2-column grids, stacked hero
- **Mobile**: single column, hamburger menu, full-width sections

## Assets
- Logo, master photo, service photos (in `/assets/`)
- Favicon set (16×16 to 180×png)
