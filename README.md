# Yinchen Tian's academic homepage

Personal academic website for Yinchen Tian (田胤辰).

Public address: https://tianyinchen56.github.io/

Adapted from [Jon Barron's website](https://github.com/jonbarron/jonbarron.github.io). See [TEMPLATE_CREDIT.md](TEMPLATE_CREDIT.md) for permission and attribution.

## Edit

- `index.html`: biography, complete campus photo, and introductions to each section.
- `research/index.html`: publications, complete paper figures, and earlier research.
- `competitions/index.html`: verified awards and complete certificate images.
- `blog/index.html`: blog landing page; no posts have been published yet.
- `site.css`: responsive customizations of the original template.
- `stylesheet.css`: adapted original Lato typography.
- `images/`: portrait and public paper figures; `images/awards/` contains certificates.
- `data/mv-actor.bib`: downloadable citation.

No framework or build step is required. To preview locally, run `python -m http.server 8765` in this folder.

GitHub Pages should publish from the root of the `main` branch. The site serves its own fonts and does not include analytics or tracking scripts.

## Add a blog post

Create `blog/your-post/index.html`, reuse the head, shared navigation, and footer from the blog index, and put the article in `<main>`. Set its own title, description, canonical URL, and Open Graph URL. Keep Blog active in navigation. Replace the empty state in `blog/index.html` with a dated link and excerpt, then add the article URL to `sitemap.xml`. No database or publishing service is needed.

## Certificate sources

The three displayed certificates were supplied by the owner and visually checked before publication. The national robot creative competition image comes from the original JPEG; the robot and AI competition and Hubei engineering competition images are complete first-page renders of the original PDFs. Images retain all four edges and their natural proportions.
