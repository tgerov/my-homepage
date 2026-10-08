# gerov.eu

Personal website for [Tsvetan Gerov](https://gerov.eu), built with [Hugo](https://gohugo.io/).

## Development

```bash
# Start dev server with live reload
hugo server

# Include draft content
hugo server -D

# Build to public/
hugo
```

## Structure

- `content/` — Markdown source files
- `layouts/` — Custom templates (override theme)
- `static/` — Static assets served at root
- `assets/` — Assets processed by Hugo Pipes
- `data/` — YAML/JSON/TOML data files
- `themes/` — Hugo theme (git submodule)
- `hugo.toml` — Site configuration

Theme files are overridden by placing equivalents under `layouts/` or `static/`. Do not edit `themes/` directly.

