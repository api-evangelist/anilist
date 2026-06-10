# AniList GraphQL API

The AniList GraphQL API v2 is the primary public developer interface for AniList.co. It exposes anime, manga, character, staff, studio, user, activity, review, recommendation, thread, comment, notification, and airing schedule data through a single endpoint at https://graphql.anilist.co. All requests are POSTs carrying a query and optional variables payload. Mutations require an OAuth2 access token. The schema includes 25+ root Query fields (Page, Media, MediaTrend, AiringSchedule, Character, Staff, MediaList, MediaListCollection, GenreCollection, MediaTagCollection, User, Viewer, Notification, Studio, Review, Activity, ActivityReply, Following, Follower, Thread, ThreadComment, Recommendation, Like, Markdown, AniChartUser, SiteStatistics, ExternalLinkSourceCollection) and 30+ root Mutation fields (UpdateUser, SaveMediaListEntry, UpdateMediaListEntries, DeleteMediaListEntry, DeleteCustomList, SaveTextActivity, SaveMessageActivity, SaveListActivity, DeleteActivity, ToggleActivityPin, ToggleActivitySubscription, SaveActivityReply, DeleteActivityReply, ToggleLike, ToggleLikeV2, ToggleFollow, ToggleFavourite, UpdateFavouriteOrder, SaveReview, DeleteReview, RateReview, SaveRecommendation, SaveThread, DeleteThread, ToggleThreadSubscription, SaveThreadComment, DeleteThreadComment, UpdateAniChartSettings, UpdateAniChartHighlights).

**Endpoint:** https://graphql.anilist.co

**Documentation:** https://docs.anilist.co/

**References:**

- Documentation: https://docs.anilist.co/
- GettingStarted: https://docs.anilist.co/guide/introduction
- APIReference: https://docs.anilist.co/reference/
