<!-- README.md is generated from README.Rmd. Please edit that file -->

# GmooG-book

This package contains the code and text for the book “Getting (more out
of) Graphics”.

# Install dependencies

Install the R packages listed in the DESCRIPTION file using

``` r
# install.packages("devtools")
devtools::install_deps() # for packages on CRAN and
devtools::install_github() # for packages only on github.
```

# Build the book

Clone the project, load it into RStudio, and build.

# PreTeXt Repository Setup

This repository now includes a starter PreTeXt layout so it can be handed off as a PreTeXt-oriented project:

- `source/main.ptx`
- `source/publication/publication.ptx`
- `source/assets/`
- `PRETEXT-MIGRATION.md`

The current manuscript is still authored in R Markdown (`*.Rmd`) and bookdown outputs (`_book/`).
Use `PRETEXT-MIGRATION.md` as the checklist for converting chapters into native PreTeXt XML.

Minimal PreTeXt build workflow from repo root:

```bash
pretext -t
pretext build web
```

Expected HTML output location:

- `output/web`

Git remotes are configured for transfer workflow:

- `origin`: `https://github.com/PreTeXtBooks/GmooG.git`
- `upstream`: `https://github.com/antonr4/GmooG-book.git`
