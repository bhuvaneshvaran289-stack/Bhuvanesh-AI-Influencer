# Plenrik — AI Influencer Marketing &amp; Ad Management HTML Template

A free, production-ready HTML template for **AI / creator-economy SaaS
products**, influencer-marketing platforms, ad-management dashboards,
and modern growth-tooling brands. Warm **off-white surface**, soft
**pastel orbital cards** (lavender, mustard, mint, coral) floating
around a centered phone-mockup hero, and a clean three-font system —
**Onest** (display) + **Albert Sans** (body) + **DM Mono** (captions).
Tokenised, responsive, accessible. No framework, no build step, no JS
dependencies.

## What makes Plenrik different

Most SaaS templates open with a left-text, right-screenshot hero. Plenrik
opens with a **centered hero headline + an "orbital" layout** — five
floating annotation cards (price tag, sold-this-week, engagement chart,
rating, live likes) positioned absolute around a centered phone showing
an influencer LIVE. The phone is the anchor; the cards are the
storytelling, like data points orbiting a moving subject. It looks
nothing like the typical "AI product" template default.

## Pages

- `index.html` — Home (centered hero with orbital floating cards · brand strip · 5-tile pastel feature bento · 3-step "how it works" · black stats strip with mustard numbers · 3 testimonial cards · black CTA banner with mustard hover)
- `product.html` — Product overview (4 alternating feature rows with pastel media tiles, integrations strip, custom-demo CTA)
- `stories.html` — Customer stories (featured mint hero + 6-card story grid with metric chips, "load more" CTA)
- `resources.html` — Resources (3-up featured posts, dense article index with date / category / read-time, newsletter sign-up banner)
- `pricing.html` — Pricing (3-tier price cards with dark featured "Scale" + mustard badge, monthly/yearly toggle, full comparison table, 6-question FAQ, trial CTA)
- `contact.html` — Contact (6 routing cards: sales · support · partnerships · press · careers · offices · plus a structured intake form)

## Tech

- Static HTML, vanilla CSS, vanilla JS (no framework, no build, no dependencies)
- Google Fonts: **Onest** (400/500/600/700 — headlines), **Albert Sans** (400/500/600/700 — body), **DM Mono** (400/500 — eyebrows / captions), with **Lobster** + **Plus Jakarta Sans** used sparingly for diverse brand-logo styles in the brand strip
- Real Unsplash photography linked directly — replace with your own assets before launch
- Reduced-motion friendly, keyboard accessible, semantic landmarks, skip-link, ARIA on interactive controls
- Responsive at 375 / 768 / 1024 / 1440

## Design system

All tokens at the top of `assets/css/styles.css`:

- **Palette** — `--paper` (#FAFAF7) warm off-white surface, `--ink` (#0F0F0F) near-black text, plus a pastel-card family: `--lavender` (#E5DCFA), `--mustard` (#F3D567), `--mint` (#C5E8CC), `--coral` (#FFD0C5), `--rose` (#FBC8D5), `--peach` (#FFDCBA)
- **Typography** — three-font system (display / body / mono), italic display weights used as emphasis (`<em>`), modular type scale
- **Spacing** — 1 → 10 modular scale
- **Motion** — single ease (`cubic-bezier(0.22, 1, 0.36, 1)`), full reduced-motion fallback
- **Layout** — 1240px container max, sticky 76px header
- **Hero gradient** — radial peach-to-cream arc behind the phone, blurred 10px

Adjust the `:root` block to recolor or rescale the whole template.
Change `--ink` and the pastel set to restyle every section across
all six pages.

## Layout archetype

- **Centered hero** with pill eyebrow, big italic-accented headline, subtitle, and two pill CTAs
- **Orbital floating cards** (`.float-card`) positioned absolute around a centerpiece phone mockup with an Instagram-style LIVE bar
- **Pastel feature bento** — 5 colored cards (2 columns wide × 2 rows), with the large lavender card spanning 2 columns and dark-ink card sitting at the bottom
- **3-step "how it works"** on a soft paper-grey background, numbered circles, plain white cards
- **Black stats strip** with mustard `~3.5rem` numbers and mono labels
- **Testimonial cards** with display-quote serif-style italic emphasis
- **Black CTA banner** with mustard subtle radial gradient + paper button hover state

## License

Free for personal and commercial projects. Attribution appreciated but
not required. Photography is linked from Unsplash; replace before
production deployment.
