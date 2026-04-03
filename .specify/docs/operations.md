# Operations — odenirdev GitHub Profile

> The profile README is a static file. Deployment is a git push to `main`. No build step, no server, no migrations.

---

## Environments

| Environment | Purpose | Access |
|---|---|---|
| `main` branch | Live profile — rendered immediately by GitHub | Public (github.com/odenirdev) |

---

## Deployment

### Standard Update
```bash
# Edit README.md
# Stage and commit
git add README.md
git commit -m "docs(profile): <change description>"
git push origin main
```

Changes are live within seconds of push — GitHub renders the README immediately.

### Rollback
```bash
# Revert to a previous commit
git revert <commit-sha>
git push origin main
```

---

## Configuration

No environment variables, secrets, or configuration files — all content is in `README.md`.

External service parameters (theme, username, badge colors) are hardcoded in image URLs within the README.

---

## Health Checks

| Check | How to verify |
|---|---|
| Profile renders | Visit `https://github.com/odenirdev` and confirm README displays |
| Stats cards load | Check that `github-readme-stats` images are not broken |
| Badges load | Check that `shields.io` badge images are not broken |
