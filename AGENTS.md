# AGENTS.md — BMAD-METHOD

## Organization
TigerEye Enterprise — Constitutional AI-driven enterprise (22-Article Constitution).

## About This Repo
BMAD (Breakthrough Method for Agile AI Driven Development) v6 — the core methodology framework powering TigerEye Enterprise. 19 agent personas across 4 phases (Analysis → Planning → Solutioning → Implementation).

## Dev Environment

**Prerequisites:**
- Node.js >= 14.0.0
- npm (comes with Node)

**Setup:**
```bash
npm install
```

**Key Commands:**
```bash
npm run build          # Build agents and teams
npm run build:agents   # Build agent definitions
npm run build:teams    # Build team configurations
npm run validate       # Validate BMAD configurations
npm run format         # Format code (Prettier)
npm run install:bmad   # Install BMAD to target project
npm run list:agents    # List available agents
```

## Architecture
- `.bmad-core/` — Core agent definitions, templates, and workflows
- `tools/` — CLI tooling for BMAD operations  
- `expansion-packs/` — Optional capability extensions
- `docs/` — Documentation and guides

## Coding Standards
- **Formatter:** Prettier (config in repo)
- **Commits:** Conventional Commits (semantic-release)
- **Reviews:** CODEOWNERS enforced
- **CI:** GitHub Actions (see `.github/workflows/`)

## Constitutional Alignment
All changes must align with TigerEye's 22-Article Constitution. Key articles:
- **Article VII** (Implicit Methodology) — BMAD IS the methodology
- **Article III** (Zero-Human-Ops) — Automate methodology delivery
- **Article XIX** (Quality Standards) — No mediocre agent definitions
