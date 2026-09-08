# ariadnaaz.github.io

Personal academic website. Plain static HTML — no framework, no build step,
no package manager. Deployed by GitHub Pages from the main branch, root folder.

## Structure
- One .html file per page, each linking to the shared style.css
- All design tokens (colors, fonts, column width) live in :root at the top of style.css
- Images and the CV PDF go in assets/

## Conventions
- Keep the nav identical across pages; move aria-current="page" to match
- Change styling in style.css only — no inline styles or per-page CSS
- Preview locally by opening index.html in a browser; no server needed
