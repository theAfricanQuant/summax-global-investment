# Summax Global Investment — website

Quarto website for Summax Global Investment Limited, an Abuja-based building
design, construction, renovation and project-management practice.

Live preview: <https://theafricanquant.github.io/summax-global-investment/>

## Pages

| File | Page |
|------|------|
| `index.qmd` | Home — positioning, how the team works, services, selected work, contact |
| `projects.qmd` | Projects — curated gallery plus the complete supplied image archive |
| `about.qmd` | About — background, objectives, services, management, contact |

Shared styling lives in `styles.css`. Images live in `assets/`.

## Editing

```bash
# one-off build into docs/
quarto render

# live reload while editing
quarto preview
```

`docs/` is the published output and is committed, because GitHub Pages serves
the site from that folder on the `main` branch. Run `quarto render` and commit
the result whenever the source changes.

## Publishing

GitHub Pages is configured as **Deploy from a branch → main → /docs**.

To refresh the public site after an edit:

```bash
quarto render
git add -A
git commit -m "Update site"
git push
```

## Content notes

- All company information, services, project names, locations and contact
  details come from the material supplied by Summax Global Investment.
- Photographs in `assets/source-archive/` are the original supplied image
  files, optimised for web delivery. They are included so no supplied artefact
  is lost; filenames are kept as labels where no fuller description was given.
- Images are resized and recompressed for the web. Originals are not stored in
  this repository.
