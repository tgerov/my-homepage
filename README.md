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

## CI/CD

On every push to `main`, Forgejo Actions:

1. Builds the Hugo site
2. Packages it into a UBI 10 + Nginx container image
3. Pushes the image to `git.unixworld.org/tsvetan/gerov.eu` (tagged `:latest` and by commit SHA)

Required repository secrets: `REGISTRY_USER`, `REGISTRY_PASSWORD`.
