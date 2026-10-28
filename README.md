# AniList

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

AniList is an anime and manga database, tracking, and social platform serving over 500,000 anime and manga entries along with character, staff, studio, user, activity, review, recommendation, and forum thread data. The primary developer surface is a free public GraphQL API at https://graphql.anilist.co, with OAuth2 authentication (Authorization Code, Implicit, and Auth Pin flows) for read/write operations against user list and social data.

**Areas:** Anime · Manga · Entertainment · Media · Social · Database · GraphQL · Authentication · Public APIs

## AniList on APIs.io

Everything profiled for AniList is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/anilist/](https://apis.io/providers/anilist/)** — or go straight to one of the APIs or properties below.

### APIs (3)

- [AniList GraphQL API v2](https://apis.io/apis/anilist/anilist-graphql-api-v2/) — The AniList GraphQL API v2 is the primary public developer interface for AniList.co. It exposes anime, manga, character, staff, studio, user, activity,…
- [AniList O Auth2 API](https://apis.io/apis/anilist/anilist-oauth2-api/) — OAuth2 authorization code and implicit grant endpoints
- [AniList Graph QL API](https://apis.io/apis/anilist/anilist-graph-ql-api/) — GraphQL query and mutation endpoint

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### GraphQL (1)

GraphQL schemas.

- [AniList GraphQL API](https://apis.io/graphqls/anilist/anilist-graphql/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Anilist Agentic Access](https://apis.io/agentic-access/anilist/anilist-agentic-access/)

#### JSON Schema (28)

The data models the API reads and writes.

- [AiringSchedule](https://apis.io/schemas/anilist/anilist-airingschedule/)
- [Character](https://apis.io/schemas/anilist/anilist-character/)
- [CharacterImage](https://apis.io/schemas/anilist/anilist-characterimage/)
- [CharacterName](https://apis.io/schemas/anilist/anilist-charactername/)
- [FuzzyDate](https://apis.io/schemas/anilist/anilist-fuzzydate/)
- [GraphQLError](https://apis.io/schemas/anilist/anilist-graphqlerror/)
- [GraphQLRequest](https://apis.io/schemas/anilist/anilist-graphqlrequest/)
- [GraphQLResponse](https://apis.io/schemas/anilist/anilist-graphqlresponse/)
- [Media](https://apis.io/schemas/anilist/anilist-media/)
- [MediaCoverImage](https://apis.io/schemas/anilist/anilist-mediacoverimage/)
- [MediaList](https://apis.io/schemas/anilist/anilist-medialist/)
- [MediaListCollection](https://apis.io/schemas/anilist/anilist-medialistcollection/)
- [MediaTag](https://apis.io/schemas/anilist/anilist-mediatag/)
- [MediaTitle](https://apis.io/schemas/anilist/anilist-mediatitle/)
- [PageInfo](https://apis.io/schemas/anilist/anilist-pageinfo/)
- [Recommendation](https://apis.io/schemas/anilist/anilist-recommendation/)
- [Review](https://apis.io/schemas/anilist/anilist-review/)
- [Staff](https://apis.io/schemas/anilist/anilist-staff/)
- [StaffImage](https://apis.io/schemas/anilist/anilist-staffimage/)
- [StaffName](https://apis.io/schemas/anilist/anilist-staffname/)
- [Studio](https://apis.io/schemas/anilist/anilist-studio/)
- [Thread](https://apis.io/schemas/anilist/anilist-thread/)
- [ThreadComment](https://apis.io/schemas/anilist/anilist-threadcomment/)
- [TokenRequest](https://apis.io/schemas/anilist/anilist-tokenrequest/)
- [TokenResponse](https://apis.io/schemas/anilist/anilist-tokenresponse/)
- …and 3 more published on APIs.io

#### JSON Structure (28)

Data models expressed in JSON Structure.

- [Anilist Airingschedule Structure](https://apis.io/json-structure/anilist/anilist-airingschedule-structure/)
- [Anilist Character Structure](https://apis.io/json-structure/anilist/anilist-character-structure/)
- [Anilist Characterimage Structure](https://apis.io/json-structure/anilist/anilist-characterimage-structure/)
- [Anilist Charactername Structure](https://apis.io/json-structure/anilist/anilist-charactername-structure/)
- [Anilist Fuzzydate Structure](https://apis.io/json-structure/anilist/anilist-fuzzydate-structure/)
- [Anilist Graphqlerror Structure](https://apis.io/json-structure/anilist/anilist-graphqlerror-structure/)
- [Anilist Graphqlrequest Structure](https://apis.io/json-structure/anilist/anilist-graphqlrequest-structure/)
- [Anilist Graphqlresponse Structure](https://apis.io/json-structure/anilist/anilist-graphqlresponse-structure/)
- [Anilist Media Structure](https://apis.io/json-structure/anilist/anilist-media-structure/)
- [Anilist Mediacoverimage Structure](https://apis.io/json-structure/anilist/anilist-mediacoverimage-structure/)
- [Anilist Medialist Structure](https://apis.io/json-structure/anilist/anilist-medialist-structure/)
- [Anilist Medialistcollection Structure](https://apis.io/json-structure/anilist/anilist-medialistcollection-structure/)
- [Anilist Mediatag Structure](https://apis.io/json-structure/anilist/anilist-mediatag-structure/)
- [Anilist Mediatitle Structure](https://apis.io/json-structure/anilist/anilist-mediatitle-structure/)
- [Anilist Pageinfo Structure](https://apis.io/json-structure/anilist/anilist-pageinfo-structure/)
- [Anilist Recommendation Structure](https://apis.io/json-structure/anilist/anilist-recommendation-structure/)
- [Anilist Review Structure](https://apis.io/json-structure/anilist/anilist-review-structure/)
- [Anilist Staff Structure](https://apis.io/json-structure/anilist/anilist-staff-structure/)
- [Anilist Staffimage Structure](https://apis.io/json-structure/anilist/anilist-staffimage-structure/)
- [Anilist Staffname Structure](https://apis.io/json-structure/anilist/anilist-staffname-structure/)
- [Anilist Studio Structure](https://apis.io/json-structure/anilist/anilist-studio-structure/)
- [Anilist Thread Structure](https://apis.io/json-structure/anilist/anilist-thread-structure/)
- [Anilist Threadcomment Structure](https://apis.io/json-structure/anilist/anilist-threadcomment-structure/)
- [Anilist Tokenrequest Structure](https://apis.io/json-structure/anilist/anilist-tokenrequest-structure/)
- [Anilist Tokenresponse Structure](https://apis.io/json-structure/anilist/anilist-tokenresponse-structure/)
- …and 3 more published on APIs.io

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Anilist Context](https://apis.io/jsonld/anilist/anilist-context/)

#### Examples (28)

Example requests and responses.

- [Anilist Airingschedule Example](https://apis.io/examples/anilist/anilist-airingschedule-example/)
- [Anilist Character Example](https://apis.io/examples/anilist/anilist-character-example/)
- [Anilist Characterimage Example](https://apis.io/examples/anilist/anilist-characterimage-example/)
- [Anilist Charactername Example](https://apis.io/examples/anilist/anilist-charactername-example/)
- [Anilist Fuzzydate Example](https://apis.io/examples/anilist/anilist-fuzzydate-example/)
- [Anilist Graphqlerror Example](https://apis.io/examples/anilist/anilist-graphqlerror-example/)
- [Anilist Graphqlrequest Example](https://apis.io/examples/anilist/anilist-graphqlrequest-example/)
- [Anilist Graphqlresponse Example](https://apis.io/examples/anilist/anilist-graphqlresponse-example/)
- [Anilist Media Example](https://apis.io/examples/anilist/anilist-media-example/)
- [Anilist Mediacoverimage Example](https://apis.io/examples/anilist/anilist-mediacoverimage-example/)
- [Anilist Medialist Example](https://apis.io/examples/anilist/anilist-medialist-example/)
- [Anilist Medialistcollection Example](https://apis.io/examples/anilist/anilist-medialistcollection-example/)
- [Anilist Mediatag Example](https://apis.io/examples/anilist/anilist-mediatag-example/)
- [Anilist Mediatitle Example](https://apis.io/examples/anilist/anilist-mediatitle-example/)
- [Anilist Pageinfo Example](https://apis.io/examples/anilist/anilist-pageinfo-example/)
- [Anilist Recommendation Example](https://apis.io/examples/anilist/anilist-recommendation-example/)
- [Anilist Review Example](https://apis.io/examples/anilist/anilist-review-example/)
- [Anilist Staff Example](https://apis.io/examples/anilist/anilist-staff-example/)
- [Anilist Staffimage Example](https://apis.io/examples/anilist/anilist-staffimage-example/)
- [Anilist Staffname Example](https://apis.io/examples/anilist/anilist-staffname-example/)
- [Anilist Studio Example](https://apis.io/examples/anilist/anilist-studio-example/)
- [Anilist Thread Example](https://apis.io/examples/anilist/anilist-thread-example/)
- [Anilist Threadcomment Example](https://apis.io/examples/anilist/anilist-threadcomment-example/)
- [Anilist Tokenrequest Example](https://apis.io/examples/anilist/anilist-tokenrequest-example/)
- [Anilist Tokenresponse Example](https://apis.io/examples/anilist/anilist-tokenresponse-example/)
- …and 3 more published on APIs.io

#### Collections (3)

Postman and Open Collection request collections.

- [AniList GraphQL API v2](https://apis.io/collections/anilist/open-anilist/)
- [AniList API v2 GraphQL API](https://apis.io/collections/anilist/open-anilist-graphql-api/)
- [AniList API v2 GraphQL OAuth2 API](https://apis.io/collections/anilist/open-anilist-oauth2-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [AniList — jsonschema rules](https://apis.io/rules/anilist/anilist-jsonschema-spectral-rules/)
- [AniList API Rules](https://apis.io/rules/anilist/anilist-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Anilist Authentication](https://apis.io/security/anilist/anilist-authentication/)
- [Anilist Domain Security](https://apis.io/security/anilist/anilist-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Anilist Scopes](https://apis.io/scopes/anilist/anilist-scopes/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://anilist.co/)
- [Documentation](https://docs.anilist.co/)
- [Getting started](https://docs.anilist.co/guide/introduction)
- [API reference](https://docs.anilist.co/reference/)
- [Pricing](https://docs.anilist.co/guide/terms-of-use#commercial-usage)
- [Blog](https://anilist.co/blog/)
- [Terms of service](https://docs.anilist.co/guide/terms-of-use)
- [Privacy policy](https://anilist.co/terms)
- [GitHub](https://github.com/AniList)

## API Evangelist rating

**Kin Score 43.1** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 78.6 |
| Contract quality | 28.5 |
| Contract governance | 13.6 |
| Operational transparency | 18.4 |
| Developer ergonomics | 71.4 |
| Access clarity | 38.2 |

**Agent readiness 36.6** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | verified |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | documented (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 34.3** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/anilist/](https://apis.io/providers/anilist/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for AniList: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/anilist/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
