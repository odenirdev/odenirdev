# Integrations — odenirdev GitHub Profile

> External services embedded in the profile README. No authentication or API keys — all integrations use public, unauthenticated URLs.

---

## shields.io

**Purpose**: Generates technology and social badge images as SVGs
**Type**: Public HTTP image CDN (embedded as `<img src>`)
**Environment**: `https://img.shields.io`

### Authentication
- **Method**: None — fully public

### Key Operations

| Badge | URL pattern | Notes |
|---|---|---|
| HTML5 | `badge/HTML5-E34F26?style=for-the-badge&logo=html5` | Orange background |
| CSS3 | `badge/CSS3-1572B6?style=for-the-badge&logo=css3` | Blue background |
| JavaScript | `badge/JavaScript-323330?style=for-the-badge&logo=javascript` | Yellow icon |
| TypeScript | `badge/TypeScript-007ACC?style=for-the-badge&logo=typescript` | Blue |
| React | `badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB` | Dark with cyan icon |
| React Native | Same URL pattern as React | Same icon, different label |
| Node.js | `badge/Node.js-339933?style=for-the-badge&logo=nodedotjs` | Green |
| Python | `badge/Python-3776AB?style=for-the-badge&logo=python` | Blue |
| Linux | `badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black` | Yellow |
| Gmail | `badge/Gmail-D14836?style=for-the-badge&logo=gmail` | Red (used as contact link) |
| LinkedIn | `badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin` | LinkedIn blue |

### Failure Behavior
- **Service unavailable**: Broken image shown — no fallback possible from static README

---

## LinkedIn

**Purpose**: Professional contact link
**Type**: External hyperlink
**URL**: `https://www.linkedin.com/in/odenirdev/`

---

## Gmail

**Purpose**: Email contact link
**Type**: `mailto:` link
**Address**: `odenirdev@gmail.com`

---

## Decommissioned Integrations

| Service | Removed | Reason |
|---|---|---|
| github-readme-stats (vercel.app) | 2026-04-03 | Service unreliable — third-party hosted with no SLA, frequent outages reported by the community |
