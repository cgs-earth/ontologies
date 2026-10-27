# CGS Ontologies

RDF ontologies published as browsable docs with [onto-to-pages](https://github.com/cgs-earth/onto-to-pages).

## Usage

- Add RDF files (`.ttl`, `.rdf`, `.jsonld`, etc.) to `src/`.
- Push to `main`; `.github/workflows/pages.yml` builds and deploys them to GitHub Pages.

## Preview locally

```bash
git clone https://github.com/cgs-earth/onto-to-pages && cd onto-to-pages
uv sync && uv run onto-to-pages ../ontologies/src -o dist
```
