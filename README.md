# borealhao.github.io
Hao Huynh's personal website and compact gallery.

## Project structure

- `index.html` — landing page and social links
- `terms.html` — commission terms page
- `gallery.html` — compact gallery of one-shots and comic chapters
- `style.css` — shared styles and gallery/lightbox presentation
- `assets/brand/` — site branding, background, and icon media
- `assets/art/` — general art assets used around the site
- `assets/comics/lamapola-blue-line/chapter-0/` — chapter 0 content for L'amapola Blue Line
  - `cover/` — cover/poster art
  - `pages/` — chapter pages in sequence
  - `lamapola-blue-line-chapter-0.pdf` — printable/export version
- `assets/icons/` — SVG navigation icons used in the lightbox

## Notes for contributors

- Keep asset paths relative to the site root.
- Store comic chapter images in a chapter-specific folder and keep page filenames sequential (`page-1.png`, `page-2.png`, etc.).
- Prefer grouping content by type and series so galleries remain easy to extend.
