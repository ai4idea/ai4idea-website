# AI4IDEA website

Source for [ai4idea.org](https://ai4idea.org), the website of AI4IDEA, the Society for Artificial Intelligence, Innovation, Development, Education & Applications.

A static site (`index.html`, `ar/index.html` for the Arabic version at `/ar/`, `styles.css`, `favicon.svg`) with no build step. Every push to `main` deploys to production on Vercel.

To preview locally: `python3 -m http.server` and open http://localhost:8000.

## Design

- Concept: "from noise to IDEA". The hero canvas assembles scattered data bits into the letters IDEA, and bits scatter away from the cursor.
- Colours: ultramarine `#2a2fdb`, ink `#0e1356`, fog `#eef0fa`, paper `#fbfbfe`, saffron `#ffc233` (used sparingly as a signal).
- Type: Archivo (expanded, heavy) for headings, Source Serif 4 for body text. Both are self-hosted in `/fonts` under the SIL Open Font License.

Repository: https://github.com/ai4idea/ai4idea-website.

## Arabic (`/ar/`)

- `ar/index.html` is a full RTL translation (`<html lang="ar" dir="rtl">`). RTL overrides live at the end of `styles.css` under `html[dir="rtl"]`.
- Type: Noto Kufi Arabic (headings) and Noto Naskh Arabic (body), self-hosted in `/fonts` under the SIL OFL and preloaded only on `/ar/`. The brand (AI4IDEA, the hero letters IDEA, the pillar letters I D E A) stays in Latin.
- Both pages link to each other through the language switch and `hreflang` alternates; both are listed in `sitemap.xml`. Keep the two pages' structure in sync when editing.
