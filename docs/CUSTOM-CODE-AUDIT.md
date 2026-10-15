# CUSTOM-CODE-AUDIT

Policy (oss-catalog.yaml): custom-authored code < 5% of delivered LOC.

## Composition

This repo is a *composition build*: every application source file is
vendored under `upstream/` (excluded from custom count by
tools/custom-code.sh markers).

Custom-authored material (all non-runtime):

- `README.md` — project documentation (excluded class: docs)
- `docs/*.md` — audit/license docs (excluded class: docs)
- `.gitignore` — config (excluded)
- `tools/custom-code.sh`, `.github/workflows/verify-build.yml` — vendored
  studio tooling (unmodified)

Runtime custom code: **none** — the explorer is delivered as vendored
upstream modules. Integration gaps called out in README are follow-up
scope for the applicant, composed the same way when picked up.

Verification: `./tools/custom-code.sh .` must exit 0 (enforced by
.github/workflows/verify-build.yml on every push/PR).
