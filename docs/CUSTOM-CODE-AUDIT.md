# CUSTOM-CODE-AUDIT

Policy (oss-catalog.yaml): custom-authored code < 5% of delivered LOC.

## Composition

This repo is a *composition build*: every application source file is
vendored under  (excluded from custom count by
tools/custom-code.sh markers).

Custom-authored material (all non-runtime):

-  — project documentation (excluded class: docs)
-  — audit/license docs (excluded class: docs)
-  — config (excluded)
- ,  — vendored
  studio tooling (unmodified)

Runtime custom code: **none** — the explorer is delivered as vendored
upstream modules. Integration gaps called out in README are follow-up
scope for the applicant, composed the same way when picked up.

Verification:  must exit 0 (enforced by
.github/workflows/verify-build.yml on every push/PR).
