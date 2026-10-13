# Repository agent policy


## Mandatory research preservation across sessions (2026-10-13)

**User directive:** For this project, preserve substantive Deep Research, market/competitor research, technical/legal reviews, architecture audits, feasibility studies, and other evidence-based investigations to GitHub by default **without waiting for another explicit reminder**, whenever the agent actually has the source and authorized GitHub write access.

- **Before research:** Inspect this repository's latest branch, existing reports and `docs/research/INDEX.md`; avoid duplicate work.
- **At completion:** Archive the complete shareable report at `docs/research/YYYY-MM-DD-topic.md` (or a faithful transcript with provenance), including date, methods, primary source links, assumptions, contradictory evidence, limits, and next experiments. Do not save only a summary when full text is available.
- **Decision hygiene:** Separate observed facts, inference, recommendations, explicit owner-approved decisions, incomplete testing, and current implementation state. Never silently convert a recommendation to an authorization.
- **Index and review:** Update `docs/research/INDEX.md`, preserve earlier conclusions, commit to a new documentation branch, and open a **Draft PR**. Do not push to main, auto-merge, or overwrite another active contributor's branch without explicit permission.
- **Privacy/safety:** Remove secrets, personal information, private user photos, cookies, signed URLs, proprietary third-party documents without permission, and other sensitive content. Respect existing safety files/guardrails. No unauthorized production deployments, billing, external communication or destructive data changes.
- **Handoff:** Always report saved path, commit SHA, and Draft PR. If tools, source material or permission are unavailable, explicitly mark **NOT SAVED** and provide save-ready content; do not pretend GitHub was updated.
- **Limits:** This repository policy guides AI agents that *load this repo*. It cannot by itself invoke GitHub tools in a separate unconnected ChatGPT chat, or guarantee storage for future research performed elsewhere. New repositories need this policy installed separately.

See `docs/research/INDEX.md` for records. Keep project-specific rules above this section in full force. A dedicated research archive repository may be used only with explicit user authorization.
