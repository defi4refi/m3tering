# OSS-LICENSES — vendored component inventory

All runtime code in this repo is vendored from upstream sources under
`upstream/`. Commit SHAs below pin the grafted revision.

| Component | Upstream | Commit | License | Obligations |
|---|---|---|---|---|
| m3terscan-monorepo | github.com/M3tering/m3terscan-monorepo | 0f5b5a18a7cedac386aa5c8eb0257914a0bcb43e | none-on-disk (applicant-authored) | Attribution retained; applicant owns upstream |
| m3terscan | github.com/M3tering/m3terscan | 2a664756f1da937ee53b5f1e57fc3aa4ace900aa | none-on-disk (applicant-authored) | Attribution retained |
| m3ters.js | github.com/M3tering/m3ters.js | c3706bc2e2471ed8c42680329bbc47386cb6271c | see upstream LICENSE | Keep copyright + license notices |
| m3ter-graphql-client | github.com/M3tering/m3ter-graphql-client | 6bc49e1524758314bb3154c443e153ba39c57cb4 | none-on-disk (applicant-authored) | Attribution retained |
| m3ter-payload-decoder | github.com/M3tering/m3ter-payload-decoder | 3d2cb43bc74512bb7b3d5473e0bb238ff06eab92 | none-on-disk (applicant-authored) | Attribution retained |
| tools/custom-code.sh | github.com/defi4refi/defi4refi (studio) | — | AGPL-3.0 | Studio tooling, unmodified |
| .github/workflows/verify-build.yml | github.com/defi4refi/defi4refi (studio) | — | AGPL-3.0 | Studio CI, unmodified |

Note: applicant-org components ship without SPDX licenses upstream; per
studio policy they are treated as source-available — obligations recorded
here, nothing banned. Applicant should add SPDX licenses upstream.

This repo itself is AGPL-3.0 (studio standard; aligns with the open-source
delivery requirement in the apply-for-build terms).
