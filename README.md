# ontology360.it

Public website of **Ontology 360** — the research matrix of the Computational Ontology project: being, knowledge and the register, read in a full circle from circumstance to constitution. Home of the book *La Constitución en la era digital* (manuscript in draft, intended for Herder, Ópera Académica; not yet submitted) and the entry point to its open companion.

One project, three sites: **Matrix** (this site) · **Project** ([computational-ontology.com](https://computational-ontology.com)) · **Platform** ([constitutionsplus.com](https://constitutionsplus.com)).

Static pages, inline CSS, self-hosted fonts (`fonts/`, OFL), no third-party code, no trackers — the same white-box practice as the project site. Visual direction “Cartography” (3 Sep 2026): white, hard rules, big type, the chain drawn as a route; the ring is the mid-page peak. Served by GitHub Pages at `ontology360.it`.

## Contents

| Path | Purpose |
|---|---|
| `index.html` | Home — the chain of five links, traceability, the three sites, the book |
| `matrix.html` | The matrix — triad, four domains, guiding question |
| `framework/` | One page per operator (Ferraris, Romero, Arendt, Todorov, Andina, Anderson, Floridi, Onnis) |
| `book.html` | Chapter map (chapter → link → companion units), three outputs, how to cite |
| `data.html` | The open companion: artefacts, fused-record schema, licences |
| `method.html` | Two-layer protocol, rules in force, decision log |
| `about.html` | Author and affiliations (publications are kept on the project site) |
| `trace/example.html` | A sample trace — illustrative values only |
| `fonts/` | Familjen Grotesk and Cormorant Garamond (variable woff2, SIL OFL) |
| `brand/` | Logo family v2 (marks light/dark, sibling marks, favicons, OG image) · `site.webmanifest` |
| `ontology360-onepage.pdf` | One-page summary: the chain and the deposited objects |
| `CNAME`, `.nojekyll`, `robots.txt`, `sitemap.xml`, `favicon.svg`, `404.html` | GitHub Pages plumbing |

## Editing

Every page is a plain HTML file; the shared stylesheet is inlined in each. If you prefer to regenerate all pages from one source, `build_site.py` (kept outside this repository) writes them from a single template.

## Publishing

1. Push to `main` in `computational-ontology/ontology360`.
2. *Settings → Pages*: source `main` / root; custom domain `ontology360.it`; enforce HTTPS once the certificate is issued.
3. DNS at the registrar: four `A` records for `@` → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`; `CNAME www` → `computational-ontology.github.io`.

## Licence

Site content: CC BY 4.0 unless stated otherwise. Maintainer: Luis Bourguet · LabOnt — Centre for Ontology, Università degli Studi di Torino · ORCID 0000-0002-4673-4486.
