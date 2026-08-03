# AniList (anilist)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

AniList is an anime and manga database, tracking, and social platform serving over 500,000 anime and manga entries along with character, staff, studio, user, activity, review, recommendation, and forum thread data. The primary developer surface is a free public GraphQL API at https://graphql.anilist.co, with OAuth2 authentication (Authorization Code, Implicit, and Auth Pin flows) for read/write operations against user list and social data.

**APIs.json:** [https://docs.anilist.co/](https://docs.anilist.co/)

## Tags

- Anime
- Manga
- Entertainment
- Media
- Social
- Database
- GraphQL
- OAuth2
- Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## APIs

### AniList GraphQL API v2

The AniList GraphQL API v2 is the primary public developer interface for AniList.co. It exposes anime, manga, character, staff, studio, user, activity, review, recommendation, thread, comment, notification, and airing schedule data through a single endpoint at https://graphql.anilist.co. All requests are POSTs carrying a query and optional variables payload. Mutations require an OAuth2 access token. The schema includes 25+ root Query fields (Page, Media, MediaTrend, AiringSchedule, Character, Staff, MediaList, MediaListCollection, GenreCollection, MediaTagCollection, User, Viewer, Notification, Studio, Review, Activity, ActivityReply, Following, Follower, Thread, ThreadComment, Recommendation, Like, Markdown, AniChartUser, SiteStatistics, ExternalLinkSourceCollection) and 30+ root Mutation fields (UpdateUser, SaveMediaListEntry, UpdateMediaListEntries, DeleteMediaListEntry, DeleteCustomList, SaveTextActivity, SaveMessageActivity, SaveListActivity, DeleteActivity, ToggleActivityPin, ToggleActivitySubscription, SaveActivityReply, DeleteActivityReply, ToggleLike, ToggleLikeV2, ToggleFollow, ToggleFavourite, UpdateFavouriteOrder, SaveReview, DeleteReview, RateReview, SaveRecommendation, SaveThread, DeleteThread, ToggleThreadSubscription, SaveThreadComment, DeleteThreadComment, UpdateAniChartSettings, UpdateAniChartHighlights).

- **Human URL:** [https://docs.anilist.co/](https://docs.anilist.co/)
- **Base URL:** `https://graphql.anilist.co`

#### Tags

- GraphQL
- Anime
- Manga
- Media
- Social

#### Properties

- [Documentation](https://docs.anilist.co/)
- [Getting Started](https://docs.anilist.co/guide/introduction)
- [Quickstart](https://docs.anilist.co/guide/graphql/)
- [API Reference](https://docs.anilist.co/reference/)
- [Authentication](https://docs.anilist.co/guide/auth/)
- [Rate Limits](https://docs.anilist.co/guide/rate-limiting)
- [Sandbox](https://studio.apollographql.com/sandbox/explorer?endpoint=https%3A%2F%2Fgraphql.anilist.co)
- [Console](https://anilist.co/settings/developer)
- [Errors](https://docs.anilist.co/guide/graphql/errors)
- [Postman Collection](collections/anilist.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/anilist.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://anilist.co/)
- [Documentation](https://docs.anilist.co/)
- [API Reference](https://docs.anilist.co/reference/)
- [Getting Started](https://docs.anilist.co/guide/introduction)
- [Quickstart](https://docs.anilist.co/guide/graphql/)
- [Authentication](https://docs.anilist.co/guide/auth/)
- [Sign Up](https://anilist.co/signup)
- [Login](https://anilist.co/login)
- [Developer Portal](https://anilist.co/settings/developer)
- [Console](https://anilist.co/settings/developer)
- [Sandbox](https://studio.apollographql.com/sandbox/explorer?endpoint=https%3A%2F%2Fgraphql.anilist.co)
- [Pricing](https://docs.anilist.co/guide/terms-of-use#commercial-usage)
- [Terms of Service](https://docs.anilist.co/guide/terms-of-use)
- [Privacy Policy](https://anilist.co/terms)
- [GitHub Organization](https://github.com/AniList)
- [GitHub Repository](https://github.com/AniList/docs)
- [Support](mailto:contact@anilist.co)
- [Contact](mailto:contact@anilist.co)
- [Blog](https://anistaff.medium.com/)
- [X (Twitter)](https://x.com/AniListco)
- [SDK](https://github.com/topics/anilist)
- [Code Examples](https://github.com/AniList/docs/tree/main/docs/guide/snippets)
- [Tools](https://github.com/yuna0x0/anilist-mcp)
- [Public APIs Listing](https://github.com/public-apis/public-apis)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
