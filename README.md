# website
## Building the site (Quarto)

The site is a [Quarto](https://quarto.org) website.

- Preview while editing: `quarto preview` (or the Render button in RStudio)
- Build: `quarto render` writes the finished site to `docs/`
- Pages and navbar: `_quarto.yml`
- Look and feel: `styles/fluent.scss` (Fluent 2 colours, cards, shadows) and `styles/fluent-dark.scss` (dark mode)
- Draft pages (`research.qmd`, `teaching.qmd`, `outreach_and_service.qmd`, `resources.qmd`) are not built until they are added to the `render:` list in `_quarto.yml`

Adding a publication: copy an existing `::: {.pub}` ... `:::` block in `publication.qmd` and edit it.

Hosting: GitHub Pages should serve from the `main` branch, `/docs` folder
(Settings → Pages → Build and deployment).
