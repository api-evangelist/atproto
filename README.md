# AT Protocol

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

AT Protocol (Authenticated Transfer Protocol) is an open, federated social networking protocol developed by Bluesky Social PBC that powers the Bluesky social network and its 40M+ users. The protocol defines a public HTTP API surface via XRPC (cross-resolver protocol calls) organized under Lexicon schemas that cover identity (DIDs and handles), repository management, feed generation, labeling, and moderation. Developers can tap into a public firehose WebSocket event stream without API keys, and write operations use OAuth 2.0 or JWT bearer tokens for authentication. All data is stored in user-owned signed repositories and is 100% publicly accessible, making the protocol suitable for building social apps, feed generators, labelers, and bots.

**Areas:** Social Network · Decentralized · Federated · Open Source · Bluesky · Fediverse · Identity · XRPC · Lexicon

## AT Protocol on APIs.io

Everything profiled for AT Protocol is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/atproto/](https://apis.io/providers/atproto/)** — or go straight to one of the APIs or properties below.

### APIs (15)

- [AT Protocol Firehose (Event Stream)](https://apis.io/apis/atproto/firehose/) — Public WebSocket event stream providing real-time access to all public activity on the AT Protocol network, including posts, likes, follows, and other…
- [AT Protocol Actor API](https://apis.io/apis/atproto/atproto-actor-api/) — Actor (user) profile, search, and preference operations
- [AT Protocol Feed API](https://apis.io/apis/atproto/atproto-feed-api/) — Feed, post, timeline, and content operations
- [AT Protocol Graph API](https://apis.io/apis/atproto/atproto-graph-api/) — Graph operations — follows, blocks, lists, and mutes
- [AT Protocol Identity API](https://apis.io/apis/atproto/atproto-identity-api/) — DID and handle resolution, identity management
- [AT Protocol Notification API](https://apis.io/apis/atproto/atproto-notification-api/) — Notification management
- [AT Protocol Repo API](https://apis.io/apis/atproto/atproto-repo-api/) — Repository management, record CRUD operations
- [AT Protocol Server API](https://apis.io/apis/atproto/atproto-server-api/) — Server management, session creation, account administration
- [AT Protocol Sync API](https://apis.io/apis/atproto/atproto-sync-api/) — Data synchronization, firehose, blob access
- [AT Protocol XRPC API](https://apis.io/apis/atproto/atproto-xrpc/) — XRPC is the AT Protocol's HTTP-based remote procedure call layer. All protocol interactions — querying records, writing records, subscribing to streams,…
- [AT Protocol Lexicon Schemas](https://apis.io/apis/atproto/lexicon/) — Lexicon is the schema definition language for AT Protocol. Every record type, XRPC method, and event subscription on the network is described by a Lexicon…
- [Personal Data Server (PDS) API](https://apis.io/apis/atproto/pds-api/) — The PDS hosts a user's repository of signed records and exposes the com.atproto.* XRPC methods for account creation, authentication, record CRUD, blob…
- [AT Protocol Relay & Firehose](https://apis.io/apis/atproto/relay-firehose/) — The Relay aggregates the com.atproto.sync.subscribeRepos firehose across PDS hosts and re-broadcasts the combined event stream over WebSocket. AppViews and…
- [Bluesky AppView API](https://apis.io/apis/atproto/bsky-appview/) — The Bluesky AppView indexes the firehose and exposes the app.bsky.* XRPC methods that the Bluesky client (and any compatible client) uses to render…
- [AT Protocol Identity (DID & Handles)](https://apis.io/apis/atproto/identity-did/) — Identity in AT Protocol is anchored in DIDs (did:plc or did:web), with human-readable handles resolved through DNS TXT records or well-known HTTP endpoints.…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Atproto Agentic Access](https://apis.io/agentic-access/atproto/atproto-agentic-access/)

#### JSON Schema (3)

The data models the API reads and writes.

- [Bluesky Post (app.bsky.feed.post)](https://apis.io/schemas/atproto/atproto-post/)
- [Bluesky Profile View Detailed (app.bsky.actor.defs#profileViewDetailed)](https://apis.io/schemas/atproto/atproto-profile/)
- [AT Protocol Session](https://apis.io/schemas/atproto/atproto-session/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Atproto Context](https://apis.io/jsonld/atproto/atproto-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [AT Protocol Vocabulary](https://apis.io/vocabularies/atproto/atproto-vocabulary/)

#### Examples (4)

Example requests and responses.

- [Atproto Createrecord Example](https://apis.io/examples/atproto/atproto-createRecord-example/)
- [Atproto Createsession Example](https://apis.io/examples/atproto/atproto-createSession-example/)
- [Atproto Getprofile Example](https://apis.io/examples/atproto/atproto-getProfile-example/)
- [Atproto Gettimeline Example](https://apis.io/examples/atproto/atproto-getTimeline-example/)

#### Collections (8)

Postman and Open Collection request collections.

- [Bluesky Application API (app.bsky) actor API](https://apis.io/collections/atproto/open-atproto-actor-api/)
- [Bluesky Application API (app.bsky) actor feed API](https://apis.io/collections/atproto/open-atproto-feed-api/)
- [Bluesky Application API (app.bsky) actor graph API](https://apis.io/collections/atproto/open-atproto-graph-api/)
- [Bluesky Application API (app.bsky) actor identity API](https://apis.io/collections/atproto/open-atproto-identity-api/)
- [Bluesky Application API (app.bsky) actor notification API](https://apis.io/collections/atproto/open-atproto-notification-api/)
- [Bluesky Application API (app.bsky) actor repo API](https://apis.io/collections/atproto/open-atproto-repo-api/)
- [Bluesky Application API (app.bsky) actor server API](https://apis.io/collections/atproto/open-atproto-server-api/)
- [Bluesky Application API (app.bsky) actor sync API](https://apis.io/collections/atproto/open-atproto-sync-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [AT Protocol — jsonschema rules](https://apis.io/rules/atproto/atproto-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Atproto Authentication](https://apis.io/security/atproto/atproto-authentication/)
- [Atproto Domain Security](https://apis.io/security/atproto/atproto-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Atproto Plans Pricing](https://apis.io/plans/atproto/atproto-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Atproto Rate Limits](https://apis.io/rate-limits/atproto/atproto-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Atproto Finops](https://apis.io/finops/atproto/atproto-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://atproto.com/)
- [Documentation](https://atproto.com/guides/overview)
- [Blog](https://atproto.com/blog)
- [GitHub](https://github.com/bluesky-social)
- [Status](https://status.bsky.app/)

## API Evangelist rating

**Kin Score 36.7** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 67.0 |
| Contract governance | 9.8 |
| Operational transparency | 26.3 |
| Developer ergonomics | 38.1 |
| Access clarity | 7.9 |

**Agent readiness 21.8** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | unknown |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 16.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/atproto/](https://apis.io/providers/atproto/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for AT Protocol: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/atproto/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
