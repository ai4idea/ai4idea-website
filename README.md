# AI4IDEA website

Source for [ai4idea.org](https://ai4idea.org), the website of AI4IDEA, the Society for Artificial Intelligence, Innovation, Development, Education & Applications.

A static site (`index.html`, `styles.css`, `favicon.svg`) with no build step. Every push to `main` deploys to production on Vercel.

To preview locally: `python3 -m http.server` and open http://localhost:8000.

## Design

- Concept: "from noise to IDEA". The hero canvas assembles scattered data bits into the letters IDEA, and bits scatter away from the cursor.
- Colours: ultramarine `#2a2fdb`, ink `#0e1356`, fog `#eef0fa`, paper `#fbfbfe`, saffron `#ffc233` (used sparingly as a signal).
- Type: Archivo (expanded, heavy) for headings, Source Serif 4 for body text. Both are self-hosted in `/fonts` under the SIL Open Font License.
