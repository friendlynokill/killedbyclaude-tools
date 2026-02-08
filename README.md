# tools.killedbyclaude.com

Miscellaneous HTML+JavaScript tools built mostly with the help of LLMs. Single-file, no build step, no framework.

Inspired by [tools.simonwillison.net](https://tools.simonwillison.net/). Part of [killedbyclaude.com](https://killedbyclaude.com).

## How it works

Each tool is a single, self-contained `.html` file with inline CSS and JavaScript. No npm, no bundler, no build step. Dependencies are loaded from CDNs.

The directory page (`index.html`) has a JavaScript tool registry — add an entry there when you add a new tool.

## Adding a new tool

1. Create a new `.html` file (use `timestamp.html` as a template for consistent styling)
2. Add an entry to the `TOOLS` array in `index.html`
3. Commit and push — GitHub Pages deploys automatically

## Structure

```
├── CNAME              # Custom domain for GitHub Pages
├── index.html         # Searchable tool directory
├── timestamp.html     # Unix timestamp converter
└── README.md
```

## Hosting

GitHub Pages, deployed from the `main` branch. Custom domain via Cloudflare DNS:

```
CNAME  tools  →  friendlynokill.github.io
```
