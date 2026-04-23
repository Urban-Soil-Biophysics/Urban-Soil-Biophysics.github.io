# Urban Soil Biophysics — website

Source for [urban-soil-biophysics.github.io](https://urban-soil-biophysics.github.io)

Built with [Quarto](https://quarto.org). Deployed automatically to GitHub Pages via GitHub Actions on every push to `main`.

## Local development

```bash
# Install Quarto: https://quarto.org/docs/get-started/
quarto preview
```

## Structure

```
_quarto.yml          # site config, navbar, footer
index.qmd            # home page
people.qmd           # team
projects.qmd         # research projects
publications.qmd     # publication list
outreach.qmd         # policy docs, talks, media
styles.css           # custom theme
files/images/        # photos and logos
.github/workflows/   # GitHub Actions deploy
```

## Updating content

- **People:** edit `people.qmd`, add photos to `files/images/people/`
- **Publications:** add entries to `publications.qmd` (top = most recent)
- **Projects:** add `.project-card` blocks to `projects.qmd`
- **Logo/favicon:** replace `files/images/logo.png` and `files/images/favicon.ico`

## Deploy

Push to `main`. The Action renders the site and pushes to the `gh-pages` branch.  
In GitHub → Settings → Pages, set source to **`gh-pages` branch, `/ (root)`**.
