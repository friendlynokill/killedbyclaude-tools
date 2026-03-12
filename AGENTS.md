Respond in English.

# Project Notes

- This repository is the standalone tools site for `tools.killedbyclaude.com`.
- Hosting: GitHub Pages, deployed from the `main` branch.
- The site is plain static HTML with no build step.

# Relationship To Main Site

- The main site repo lives one level up, at `../`.
- The main site is a separate Hugo project deployed on Cloudflare Pages.
- Navigation and branding should stay roughly aligned across both repos.
- Keep git operations separate from the main site repo.

# Files

- `index.html` is the tools landing page.
- Individual tools currently include `timestamp.html` and `bill.html`.
- `CNAME` controls the custom domain for GitHub Pages.
