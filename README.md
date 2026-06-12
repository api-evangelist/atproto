# AT Protocol (atproto)

AT Protocol (Authenticated Transfer Protocol) is an open, federated social networking protocol developed by Bluesky Social PBC that powers the Bluesky social network and its 40M+ users. The protocol exposes a public HTTP XRPC API organized under Lexicon schemas covering identity (DIDs and handles), repository management, feed generation, labeling, and moderation. Developers can access a public firehose WebSocket event stream without API keys, and write operations use OAuth 2.0 or JWT bearer tokens for authentication.

- **APIs.json**: [https://raw.githubusercontent.com/api-evangelist/atproto/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/atproto/refs/heads/main/apis.yml)
- **Naftiko Fleet**: [https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=atproto-api-evangelist&utm_content=repo](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=atproto-api-evangelist&utm_content=repo)

## Tags

Social Networking, Decentralized, Federated, Open Source, Bluesky, Fediverse, Identity, XRPC, Lexicon

## APIs

| API | Description | Docs |
|-----|-------------|------|
| AT Protocol Core API (com.atproto) | Core XRPC API covering server identity, repository management, account administration, moderation/labeling, and data sync | [Docs](https://atproto.com/specs/xrpc) |
| Bluesky Application API (app.bsky) | Application-layer Lexicon API for feeds, actors, graph, notifications, and video | [Docs](https://docs.bsky.app/docs/advanced-guides/atproto) |
| AT Protocol Firehose | Public WebSocket event stream for real-time access to all public network activity — no API key required | [Docs](https://atproto.com/specs/event-stream) |

## Plans / Rate Limits / FinOps

| Resource | File |
|----------|------|
| Plans & Pricing | [plans/atproto-plans-pricing.yml](plans/atproto-plans-pricing.yml) |
| Rate Limits | [rate-limits/atproto-rate-limits.yml](rate-limits/atproto-rate-limits.yml) |
| FinOps | [finops/atproto-finops.yml](finops/atproto-finops.yml) |

## Timestamps

- **Created**: 2026-06-12
- **Modified**: 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | https://atproto.com/ |
| Documentation | https://atproto.com/guides/overview |
| Blog | https://atproto.com/blog |
| GitHub Organization | https://github.com/bluesky-social |
| LinkedIn | https://www.linkedin.com/company/bluesky-pbc |
| X (Twitter) | https://twitter.com/at_protocol |
| Status Page | https://status.bsky.app/ |
| TypeScript SDK | https://github.com/bluesky-social/atproto/tree/main/packages |
| Go SDK (Indigo) | https://github.com/bluesky-social/indigo |

## Maintainers

- **Kin Lane** — [kin@apievangelist.com](mailto:kin@apievangelist.com)
