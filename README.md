# Hydromancer

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Hydromancer is data infrastructure for the Hyperliquid ecosystem, offering real-time REST and WebSocket APIs, L2/L4 orderbook streaming, liquidations feeds, oracle and perp/spot price data, HIP-3/HIP-4 market events, and granular historical datasets (via its Reservoir exports). The REST API is a single POST /info dispatcher with Bearer-token authentication and token-metered subscription pricing; the WebSocket API delivers low-latency streams with tiered connection and subscription limits. Documentation is agent-native (llms.txt plus Markdown twins of every page). Onboarding is manual, with a discretionary free tier for public-goods and early-stage teams.

**Areas:** Hyperliquid · Blockchain · Web3 · DeFi · Crypto trading data · Market Data · Real-Time · WebSocket streaming · Historical Data · Orderbook data

## Hydromancer on APIs.io

Everything profiled for Hydromancer is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/hydromancer-leading-hyperliquid-data-provider/](https://apis.io/providers/hydromancer-leading-hyperliquid-data-provider/)** — or go straight to one of the APIs or properties below.

### APIs (2)

- [Hydromancer REST API](https://apis.io/apis/hydromancer-leading-hyperliquid-data-provider/hydromancer-rest-api/) — Hyperliquid data REST API using a single POST /info operation dispatcher (type field selects the operation). Bearer-token authentication. Provides user…
- [Hydromancer WebSocket API](https://apis.io/apis/hydromancer-leading-hyperliquid-data-provider/hydromancer-websocket-api/) — Real-time WebSocket streams for Hypercore events, orderbooks (L2/L4), trades, and account updates. API key passed as a query parameter.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [Hydromancer MCP Server](https://apis.io/servers/hydromancer-leading-hyperliquid-data-provider/hydromancer-mcp-server/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Hydromancer Leading Hyperliquid Data Provider Authentication](https://apis.io/security/hydromancer-leading-hyperliquid-data-provider/hydromancer-leading-hyperliquid-data-provider-authentication/)
- [Hydromancer Leading Hyperliquid Data Provider Domain Security](https://apis.io/security/hydromancer-leading-hyperliquid-data-provider/hydromancer-leading-hyperliquid-data-provider-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Hydromancer Leading Hyperliquid Data Provider Plans Pricing](https://apis.io/plans/hydromancer-leading-hyperliquid-data-provider/hydromancer-leading-hyperliquid-data-provider-plans-pricing/)

#### Rate limits (2)

Published request limits.

- [Hydromancer Leading Hyperliquid Data Provider Rate Limits](https://apis.io/rate-limits/hydromancer-leading-hyperliquid-data-provider/hydromancer-leading-hyperliquid-data-provider-rate-limits/)
- [Hydromancer Leading Hyperliquid Data Provider Websocket Rate Limits](https://apis.io/rate-limits/hydromancer-leading-hyperliquid-data-provider/hydromancer-leading-hyperliquid-data-provider-websocket-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://hydromancer.xyz)
- [Documentation](https://docs.hydromancer.xyz)
- [API reference](https://docs.hydromancer.xyz/readme/rest-api)
- [Pricing](https://docs.hydromancer.xyz/readme/pricing)
- [Support](https://hydromancer.xyz/contact)
- [Blog](https://hydromancer.xyz/blog)

## API Evangelist rating

**Kin Score 30.8** — thin · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 71.7 |
| Contract quality | 0.0 |
| Contract governance | 0.0 |
| Operational transparency | 55.3 |
| Developer ergonomics | 42.9 |
| Access clarity | 42.1 |

**Agent readiness 11.4** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 16.7** — Securities & Market Data

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/hydromancer-leading-hyperliquid-data-provider/](https://apis.io/providers/hydromancer-leading-hyperliquid-data-provider/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Hydromancer: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/hydromancer-leading-hyperliquid-data-provider/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
