# Yinchen Tian's academic homepage

Personal academic website for Yinchen Tian (田胤辰).

Public address: https://tianyinchen56.github.io/

Adapted from [Jon Barron's website](https://github.com/jonbarron/jonbarron.github.io). See [TEMPLATE_CREDIT.md](TEMPLATE_CREDIT.md) for permission and attribution.

## Edit

- `index.html`: biography, complete campus photo, and introductions to each section.
- `research/index.html`: publications, complete paper figures, and earlier research.
- `competitions/index.html`: nine verified award records from 2023–2025, grouped by year, with complete certificates.
- `blog/index.html`: blog index.
- `blog/spatial-consistency-world-models/index.html`: Chinese article adapted from the owner's presentation, with seven figures and primary-source references.
- `site.css`: responsive customizations of the original template.
- `stylesheet.css`: adapted original Lato typography.
- `images/`: portrait and public paper figures; `images/awards/` contains certificates.
- `data/mv-actor.bib`: downloadable citation.

No framework or build step is required. To preview locally, run `python -m http.server 8765` in this folder.

GitHub Pages publishes from the root of the `main` branch. Fonts and content images are served locally. At the owner's request, the homepage includes a Flag Counter image that counts visits and displays approximate IP-based country/region locations. It does not request browser geolocation. No analytics JavaScript is included.

## Add a blog post

Create `blog/your-post/index.html`, reuse the head, shared navigation, and footer from the existing article, and put the article in `<main>`. Set its own language, title, description, canonical URL, Open Graph metadata, and structured data. Keep Blog active in navigation. Add a dated link and excerpt to `blog/index.html`, then add the article URL to `sitemap.xml`. No database or publishing service is needed.

## Certificate sources

The displayed certificates were supplied by the owner and visually checked before publication. JPEG/PNG certificates are used whole, and PDF certificates are rendered as complete pages. Images retain all four edges and their natural proportions. The 2023 engineering-drawing certificate confirms a Hubei provincial second prize. The two 2024 3D-design certificates are previews, visibly labeled as such. Source provenance for added awards and article figures is recorded in `data/content-sources.json`.

## Visitor map

The homepage uses counter `hWmx`: https://info.flagcounter.com/hWmx. Its image is embedded directly so real homepage requests are counted. Statistics begin when installed on October 13, 2026 and do not recover earlier visits. Location is approximate and can reflect VPN/proxy exits. The provider may be unavailable or blocked for some visitors; the rest of the page and a direct statistics link remain usable. This counter was created without an email or management account.
