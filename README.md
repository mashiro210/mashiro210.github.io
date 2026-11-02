# Mashiro Okada — Academic Website

Source for [mashiro210.github.io](https://mashiro210.github.io/), built with Hugo Blox and deployed with GitHub Pages.

## Repository structure

| Path | Purpose |
| --- | --- |
| `content/_index.md` | Home page and latest updates |
| `content/publications.md` | Publications page |
| `content/presentations.md` | Conference presentations |
| `content/updates.md` | Full updates feed |
| `content/authors/admin/_index.md` | Profile, education, experience, awards, and links |
| `static/files/mashiro_okada_academic_cv.pdf` | Public downloadable CV |
| `assets/css/custom.css` | Site-specific styling |
| `config/_default/menus.yaml` | Primary navigation |

The editable LaTeX CV source is maintained separately in the private `academic-cv` repository. This repository stores only the PDF published on the website.

## Local preview

Requirements: Hugo Extended, Go, Node.js, and pnpm.

```bash
pnpm install
hugo server --disableFastRender
```

Open the local URL printed by Hugo and check both light and dark themes.

## Production build

```bash
hugo --minify --cleanDestinationDir --forceSyncStatic
```

The build output is written to `public/`.

## Updating the website

1. Edit the relevant Markdown file under `content/`.
2. Compile the latest CV in the private `academic-cv` repository.
3. Replace `static/files/mashiro_okada_academic_cv.pdf` with the compiled PDF.
4. Run the production build and inspect the affected page locally.
5. Commit and push to `main`.

Pushing to `main` starts the GitHub Pages deployment through `.github/workflows/deploy.yml`.

## Content rules

- Use the latest verified academic CV as the authoritative source.
- Do not add review status, links, or explanatory notes unless they are explicitly intended for publication.
- Keep full author lists where the source provides them; do not infer missing authors.
- Keep presentation citations unnumbered on the website.
