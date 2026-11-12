# SpiritAmmo — legal documents

Public hosting for the legal documents referenced by the
[SpiritAmmo](https://github.com/danteata/spiritammo) app's store listings.
The app's own source repository is private, so these live here instead.

| Document | URL |
|---|---|
| Privacy Policy | https://danteata.github.io/spiritammo-legal/ |
| Delete your account | https://danteata.github.io/spiritammo-legal/delete-account/ |

## Editing

`index.html` is the published page. The canonical source is
`PRIVACY_POLICY.md` in the app repository — **edit that first**, then mirror the
change here so the two cannot drift.

The policy describes real data flows in the app (speech recognition, Clerk,
Convex, Gemini, ElevenLabs, analytics consent). If you add a third-party SDK, a
Convex table holding user data, or an external crash reporter, both copies need
updating in the same change.
