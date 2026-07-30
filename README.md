# Lcstoshio.github.io

Personal academic website and public research resources.

- Website: <https://lcstoshio.github.io/>
- BHRC Research Data Guide: <https://lcstoshio.github.io/BHRC/>

Each larger page has its own source folder under [`pages/`](pages/):

- [`main-site/`](pages/main-site/) is the homepage and academic website.
- [`BHRC/`](pages/BHRC/) is the BHRC Research Data Guide.
- Each tutorial and standalone project has its own sibling folder.

GitHub Actions combines these folders only when deploying GitHub Pages. This
keeps the repository root clean without changing any public URLs.
