# Canongate AI. Landing Page

Intended URL path: /for/canongate-ai

Bespoke one-page working paper for Tim Hurst and Simon Catley, co-founders of Canongate AI Ltd (Edinburgh, Roslin). Built to read like a short, well-typeset document rather than a startup pitch page: parchment ground, near-black ink, one gold rule, Fraunces for the title block, Inter for the body, JetBrains Mono for any figure or code. Handed over at booth SS9, eMerge Americas Miami 2026.

## Files

- `index.html`. The single-page paper.
- `styles.css`. Token-mapped from `Brand Pack/brand-pack.json`.
- `logo.svg`. Typographic wordmark (brand pack had no recoverable logo; this is a minimal placeholder in the brand's own type).

## Voice

Prospect's voice, Edinburgh restraint. No em dashes, no antithesis, no performed questions, no hype. Evidence where it exists, scope language where pricing would otherwise sit.

## Hard requirements honoured

- No Eduba branding at the top. Eduba appears only in the footer as "Prepared by Eduba, eduba.io".
- No pricing for Eduba work. Scope language only.
- All external URLs are real anchors with `target="_blank" rel="noopener"`.
- NLP Logix reference includes "in machine learning since 2011" and "over 150 data scientists".
- KPMG UK framed as "(Big Four)".
- Ethics Engine mention carries the one-sentence bio and real links to arxiv.org/abs/2510.11742 and github.com/RinDig/AuditEngine.
- "1,500+" phrasing used for people trained.
- No JS. Mobile-responsive at 375px.

## CTA

Matt Creamer, Eduba CRO. https://calendly.com/thecro-eduba/30min

## Hosting note

Deploy under `/for/canongate-ai` on the Eduba conference host. The three files (`index.html`, `styles.css`, `logo.svg`) sit together, no build step required.
