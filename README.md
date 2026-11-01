# Soveren

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

Soveren is a unified Data Security Posture Management (DSPM) and Data Detection and Response (DDR) platform that delivers real-time data observability for Kubernetes and cloud environments. It combines at-rest data detection with eBPF-based network traffic analysis to discover sensitive assets, map the data flows between services, detect misconfigurations (public or unencrypted S3 buckets, unencrypted RDS/network), and audit compliance posture against PCI DSS, GDPR, and CPRA. Soveren exposes a read-only Object API over the discovered inventory and an outbound webhook event surface for automation. A portfolio company of Northzone.

**Areas:** Company · Infra Devtools · Data Security · DSPM · DDR · Privacy · Kubernetes · Compliance · Security

## Soveren on APIs.io

Everything profiled for Soveren is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/soveren/](https://apis.io/providers/soveren/)** — or go straight to one of the APIs or properties below.

### APIs (6)

- [Soveren Assets API](https://apis.io/apis/soveren/soveren-assets-api/) — The Assets API from Soveren — 4 operation(s) for assets.
- [Soveren Data Types API](https://apis.io/apis/soveren/soveren-data-types-api/) — The Data Types API from Soveren — 1 operation(s) for data types.
- [Soveren Endpoints API](https://apis.io/apis/soveren/soveren-endpoints-api/) — The Endpoints API from Soveren — 2 operation(s) for endpoints.
- [Soveren Kafka API](https://apis.io/apis/soveren/soveren-kafka-api/) — The Kafka API from Soveren — 4 operation(s) for kafka.
- [Soveren S3 API](https://apis.io/apis/soveren/soveren-s3-api/) — The S3 API from Soveren — 2 operation(s) for s3.
- [Soveren SQL DB API](https://apis.io/apis/soveren/soveren-sql-db-api/) — The SQL DB API from Soveren — 5 operation(s) for sql db.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (2)

Event-driven and webhook contracts.

- [Soveren Events (Webhooks)](https://apis.io/asyncapis/soveren/soveren-events-asyncapi/)
- [Soveren Webhooks](https://apis.io/asyncapis/soveren/soveren-webhooks/)

#### Event channels (1)

Individual events and webhooks the provider emits.

- [/](https://apis.io/channels/soveren/events/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [soveren](https://apis.io/servers/soveren/soveren/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Soveren Agentic Access](https://apis.io/agentic-access/soveren/soveren-agentic-access/)

#### Collections (6)

Postman and Open Collection request collections.

- [Soveren Object Assets API](https://apis.io/collections/soveren/open-soveren-assets-api/)
- [Soveren Object Assets Data Types API](https://apis.io/collections/soveren/open-soveren-data-types-api/)
- [Soveren Object Assets Endpoints API](https://apis.io/collections/soveren/open-soveren-endpoints-api/)
- [Soveren Object Assets Kafka API](https://apis.io/collections/soveren/open-soveren-kafka-api/)
- [Soveren Object Assets S3 API](https://apis.io/collections/soveren/open-soveren-s3-api/)
- [Soveren Object Assets SQL DB API](https://apis.io/collections/soveren/open-soveren-sql-db-api/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Soveren Object Api Overlay](https://apis.io/overlays/soveren/soveren-object-api-overlay/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Soveren Authentication](https://apis.io/security/soveren/soveren-authentication/)
- [Soveren Domain Security](https://apis.io/security/soveren/soveren-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://soveren.io)
- [Documentation](https://docs.soveren.io/en/stable/)
- [Getting started](https://docs.soveren.io/en/stable/)
- [API reference](https://docs.soveren.io/en/stable/integration/api/ref/)
- [Sign up](https://app.soveren.io/sign-up)
- [Support](https://soveren.io/get-a-demo)
- [Blog](https://soveren.io/blog)
- [Terms of service](https://assets.website-files.com/60ebf6ae3b0fe3c5e739324f/60ebf6ae3b0fe306a53933ce_Soveren_Website_Terms_of_Use_20102020.pdf)
- [Privacy policy](https://soveren.io/privacy-policy)

## API Evangelist rating

**Kin Score 39.6** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 53.4 |
| Contract governance | 4.5 |
| Operational transparency | 7.9 |
| Developer ergonomics | 58.9 |
| Access clarity | 21.1 |

**Agent readiness 29.5** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | yes |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | distinct |

**Regulatory alignment 24.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/soveren/](https://apis.io/providers/soveren/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Soveren: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/soveren/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
