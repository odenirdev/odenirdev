# Architecture — odenirdev GitHub Profile

> The profile is a single Markdown file rendered by GitHub. There is no application code, build step, or server. Content is static; dynamic elements are rendered client-side via external image URLs.

---

## System Overview

The repository contains one file (`README.md`), written in pure Markdown. GitHub renders it automatically as the public profile page. Badges are static SVG images embedded via Markdown image syntax (`![alt](url)`) served from `shields.io`.

---

## Component Map

```
README.md
├── Bio section          — inline HTML (<p> tags)
├── Badges section       — <img> pointing to shields.io
│   ├── Language badges  — HTML5, CSS3, JavaScript, TypeScript
│   ├── Framework badges — React, React Native, Node.js, Python
│   └── OS badge         — Linux
└── Contact section      — <a> href links (mailto, linkedin)
```

---

## Components

### Bio section
- **Responsibility**: Presents name, role, current focus, and collaboration interest
- **Location**: Lines 1–10 of README.md

### Badges section
- **Responsibility**: Visually communicates the technology stack
- **Dependencies**: `shields.io` — external CDN, no authentication
- **Location**: Lines 18–34 of README.md

### Contact section
- **Responsibility**: Provides clickable links to Gmail and LinkedIn
- **Location**: Lines 40–45 of README.md

---

## Known Constraints

- No build pipeline — changes take effect immediately on push to `main`
- External image services (shields.io, github-readme-stats) are not under project control; outages affect visual rendering
- GitHub profile README has no custom domain, routing, or server-side logic
