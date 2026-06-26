---
status: done
type: chore
priority: high
area: devops
---

## Fork & Rebrand: urocissa → picasu

Forked into standalone project **picasu** with renamed crate, env vars, CI, directories, and documentation.

### Completed

1. **Rust crate rename** — `urocissa` → `picasu` in `Cargo.toml`, binary names (`picasu`, `picasu-openapi`), imports, xtask refs
2. **Environment variables** — `UROCISSA_*` → `PICASU_*` across all source, config, Docker, CI, docs
3. **Directory restructure** — `gallery-backend/` → `server/`, `gallery-frontend/` → `frontend/`
4. **Trimming** — Removed `gallery-site/`, PowerShell scripts, NSIS installer, Windows docs, Windows CI job
5. **CI/CD** — Updated Docker image refs, GitHub Actions workflows, release artifact names
6. **Frontend** — Updated page titles, route titles, Playwright launcher, env var refs
7. **Tests** — Updated placeholder filenames, EXIF Software tags, test bootstrap structs
8. **Documentation** — Updated `README.md`, `AGENTS.md`, `docs/*`, `.gitignore`, `.claude/`, `.plan/` refs
9. **Branding assets** — placeholder (logo/favicon not yet replaced)
10. **License** — copyright holder not yet updated
