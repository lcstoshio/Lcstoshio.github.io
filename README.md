# Lucas Toshio Ito — websites and tutorials

This repository contains the source files published at
<https://lcstoshio.github.io/>.

## Maintained pages

| Page | Public URL | Status |
| --- | --- | --- |
| Main academic site | <https://lcstoshio.github.io/> | Active |
| BHRC Research Data Guide | <https://lcstoshio.github.io/BHRC/> | Active |
| R Markdown tutorial | <https://lcstoshio.github.io/Tutorial_RMarkdown/> | Maintained until the Quarto replacement is ready |
| ggplot2 tutorial | <https://lcstoshio.github.io/Tutorial_ggplot2/> | Quarto source restored; English translation planned |

Source files for these pages live in [`pages/`](pages/). The deployment
workflow publishes the main site at the root URL and each tutorial or guide at
its existing subdirectory URL.

## Roadmap

1. Create `Tutorial_Quarto` as a simple, practical successor to
   `Tutorial_RMarkdown`, using a similar teaching format.
2. Translate `Tutorial_ggplot2` into English.

The maintained ggplot2 source is
[`Tutorial_Graficos_V2.qmd`](pages/Tutorial_ggplot2/Tutorial_Graficos_V2.qmd).

## Archived pages

Older experiments and unused pages are preserved in
[`archive/legacy-pages/`](archive/legacy-pages/) for reference. They are not
included in the GitHub Pages deployment. This includes the retired graphPRS
tutorial.

## Deployment

GitHub Actions deploys the site after changes are pushed to `main`. The
workflow is defined in [`.github/workflows/pages.yml`](.github/workflows/pages.yml).
