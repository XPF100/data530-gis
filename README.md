# data530-gis

Course materials and hosting for DATA 530, Introduction to GIS: a fully online, asynchronous course on GIS for public health using ArcGIS Online.

The site is a [Quarto](https://quarto.org) website. Every push to `main` rebuilds it and publishes it to GitHub Pages through `.github/workflows/publish.yml`.

## Layout

| Path | What it is |
|---|---|
| `_quarto.yml` | Site settings and navigation |
| `index.qmd`, `schedule.qmd`, `readings.qmd` | Home, schedule and assigned readings |
| `weeks/week-0N/index.qmd` | Each week's overview page |
| `weeks/week-01/slides.qmd` | Week 1 slides (reveal.js; press `S` for speaker notes) |
| `weeks/week-01/handout.qmd` | Week 1 handout and cheat sheet (HTML and PDF) |
| `weeks/week-01/images/` | Diagrams used in the slides |

## Editing

Edit any `.qmd` file and push to `main`. To preview locally, install Quarto and run `quarto preview`.

## Publishing setup (one time)

In the repository's **Settings → Pages**, set **Source** to **GitHub Actions**. On a free GitHub plan, Pages publishes only from a public repository.

## What does not belong here

No copyrighted material (the textbook, its figures, or paywalled papers: link to DOIs instead) and nothing about individual students. Grades and submissions stay in Canvas.
