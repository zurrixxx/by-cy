# by cy

Personal writings and notes by Charles Yang.

🌐 **Live site:** https://zurrixxx.github.io/by-cy/

## Local Development

```bash
# Install MkDocs Material
pip install mkdocs-material

# Serve locally (hot reload)
mkdocs serve

# Build static site
mkdocs build
```

## Structure

```
docs/
├── index.md          # Homepage
├── about.md          # About page
├── essays/           # Long-form writing
│   └── index.md
└── notes/            # Quick notes
    └── index.md
```

## Adding Content

1. Create a new `.md` file in the appropriate folder
2. Update `mkdocs.yml` nav section if needed
3. Commit and push — auto-deploys to GitHub Pages
