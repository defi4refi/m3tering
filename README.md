# m3tering-explorer

Explorer for the [M3tering Protocol](https://docs.m3ter.ing/) — trustless energy
tracking for decentralised applications.

Built by the **defi4refi** studio in response to
[defi4refi/defi4refi#1](https://github.com/defi4refi/defi4refi/issues/1).

Composed entirely from vendored upstream modules (see ); custom
code is <5% of LOC per studio policy — see .

## What's inside

| Path | Source | What it provides |
|---|---|---|
|  | github.com/M3tering/m3terscan-monorepo | Explorer app (Next.js): protocol stats, per-m3ter pages, energy/revenue charts, map, blocks, search |
|  | github.com/M3tering/m3terscan | Alternate React-Router/Vite explorer + API client |
|  | github.com/M3tering/m3ters.js | Names & avatars for m3ters/contracts/accounts |
|  | github.com/M3tering/m3ter-graphql-client | Typed client for subgraph.m3ter.ing |
|  | github.com/M3tering/m3ter-payload-decoder | Payload decoding/validation tool |

## Run



The app reads the public subgraph at  and chain RPCs —
no keys needed to explore read-only data.

## Coverage vs the application ask

Covered by vendored modules: cumulative stats & graphs, per-m3ter
energy/revenue charts, raw transaction info, friendly names+avatars
(m3ters.js), map view, payload decoding tools.

Follow-ups for the applicant (see issue thread): state-diff tracker depth,
rollup proposal/validity views, Waku/Streamr realtime feed, apps directory.

## License

AGPL-3.0 — see LICENSE. Vendored component licenses are inventoried in
docs/OSS-LICENSES.md.
