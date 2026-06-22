
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Cavan Donohoe

[![Website](https://img.shields.io/badge/site-cavandonohoe.github.io-1f6feb?logo=github)](https://cavandonohoe.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-cavan--donohoe-0a66c2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/cavan-donohoe/)
[![Email](https://img.shields.io/badge/email-cavandonohoe%40gmail.com-informational?logo=gmail&logoColor=white)](mailto:cavandonohoe@gmail.com)

## About me

I’m a data scientist and statistical programmer. I’ve been writing R
day-to-day since 2019 (7+ years), mostly building R packages, data
pipelines, and validated reporting for clinical research.
Reproducibility, code review, and audit-readiness are the baseline for
everything I ship.

Alongside the data-science work, I’ve leaned hard into the software
engineering side of the craft: package design, testing, CI/CD,
deployment, and the tooling that keeps an analytics codebase honest as
it grows. I’m now actively looking for roles where both halves matter.

## What I work on

- 📦 **R package development** with `roxygen2`, `testthat`, `pkgdown`,
  and `renv`
- 📊 **Automated tables, figures, and listings** with `gt` and `ggplot2`
- 🧪 **Statistical computing for clinical research**, including
  independently coded analyses validated against production outputs
- 🔁 **Reproducible pipelines** with pinned dependencies, deterministic
  builds, and scheduled data refreshes
- 🌐 **Web and dashboard work** in Shiny, R Markdown / Quarto, and
  Next.js

## Featured projects

| Project | What it is | Stack |
|----|----|----|
| [**cavandonohoe.github.io**](https://github.com/cavandonohoe/cavandonohoe.github.io) | Personal site built from R Markdown, rebuilt by GitHub Actions on every push. Scheduled workflows refresh datasets from public sources (Zillow, IMDb, S&P 500, box-office); lint, typo, link, accessibility, and Lighthouse checks run on every PR. | R Markdown · GitHub Pages · GitHub Actions |
| [**rent-vs-buy**](https://github.com/cavandonohoe/rent-vs-buy) | Interactive Shiny app comparing buying vs. renting + investing, with amortization, breakeven sweeps, and equity over time. Deployed to shinyapps.io. | R · Shiny · plotly |
| [**confederate_statues**](https://github.com/cavandonohoe/confederate_statues) | Web-scraping pipeline that builds a dated timeline of Confederate-monument installations from Wikipedia. | R · `rvest` · `ggplot2` |

## Data science

What I do most of the time. The clinical reporting work itself is
private (regulated data), but the patterns transfer:

- **Validated, audit-ready analyses.** Independent coding against
  production outputs is a normal part of my workflow. I’m used to
  writing code that someone else verifies line-by-line.
- **Tables, figures, and listings at scale.** Automated TFL pipelines
  using `gt` and `ggplot2`, parameterized so the same code produces
  outputs for different analysis sets, populations, and timepoints.
- **Statistical methods.** Survival, weighted analyses, proportions with
  Wilson, modified Wilson, Clopper-Pearson, and Simel CIs, plus
  sensitivity and specificity for diagnostic tests.
- **Data wrangling.** `tidyverse` end-to-end; SQL for upstream pulls;
  AWS S3 for tidy datasets.

## Software engineering

Engineering habits I bring to every codebase I own:

- **Package design.** Exported functions have roxygen docs and examples;
  edge cases have `testthat` tests; releases are reproducible with
  `renv`; breaking changes go through code review and changelogs.
- **CI/CD.** Every public repo I own runs CI. The [website
  repo](https://github.com/cavandonohoe/cavandonohoe.github.io/tree/main/.github/workflows)
  is the clearest example: 20+ GitHub Actions workflows covering
  `lintr`, typo checks, link checks, accessibility (`pa11y`),
  Lighthouse, Dependabot, scheduled data refreshes, and pages deploys.
- **Reproducibility.** Pinned dependency versions, deterministic builds,
  documented inputs and outputs. If a chart is on my site, the code and
  the data refresh that produced it are in the repo.
- **Deployment.** Comfortable shipping to GitHub Pages, shinyapps.io,
  Posit Connect, Supabase, and Vercel.
- **Beyond R.** Side projects in TypeScript / Next.js / Supabase
  (pairwise rankers, scheduling apps) and Python (microdata
  reconstructions). Most are private; happy to walk through code.

## Tech stack

**Languages.** R · SQL · Python · TypeScript · Bash

**R ecosystem.** tidyverse · `gt` · `ggplot2` · `shiny` · `roxygen2` ·
`testthat` · `pkgdown` · `renv` · `rmarkdown` / Quarto

**Data & cloud.** PostgreSQL · AWS S3 · Supabase · Posit Connect ·
shinyapps.io

**Tooling.** Git / GitHub · GitHub Actions · GitLab CI · Docker (basic)
· pre-commit · `lintr`

## Contact

- 🌐 [cavandonohoe.github.io](https://cavandonohoe.github.io/)
- 💼 [LinkedIn](https://www.linkedin.com/in/cavan-donohoe/)
- ✉️ <cavandonohoe@gmail.com>
