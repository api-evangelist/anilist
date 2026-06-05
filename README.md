# AniList (anilist)

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
