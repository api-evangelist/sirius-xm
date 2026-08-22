# Sirius XM

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

Sirius XM Holdings is the leading audio entertainment company in North America, providing satellite radio, digital streaming, podcast, and advertising services through SiriusXM, Pandora, and AdsWizz brands. The Pandora Developer API enables partners to build personalized music and podcast streaming experiences using GraphQL. AdsWizz provides programmatic audio advertising APIs for ad insertion, targeting, and measurement.

**URL:** [https://raw.githubusercontent.com/api-evangelist/sirius-xm/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sirius-xm/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Audio
- Streaming
- Radio
- Music
- Podcast
- Advertising
- Entertainment

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-02

## APIs

### Pandora Developer API

The Pandora Developer API provides GraphQL-based access to Pandora's music catalog of over 30 million tracks, stations, podcasts, and playlists. It supports personalized playback, search, user feedback (thumbs up/down), collection management, and listener profile data. Authentication uses OAuth2. Available to approved partner applications through the Pandora Developer Center.

**Human URL:** https://developer.pandora.com/

#### API Categories (GraphQL)

- **Playback** - Trigger playback from search, curated lists, user collections, or recommendations
- **Podcast** - Access podcasts and podcast episodes
- **Search** - Full-text catalog search for artists, songs, stations, playlists, and podcasts
- **Collection** - Manage a listener's personalized music library
- **Feedback** - Submit thumbs up/down ratings to personalize recommendations
- **Profile** - Access listener profile, bio, followers, and following data

#### Properties

- [Documentation](https://developer.pandora.com/docs/key-concepts/apis/)
- [Developer Portal](https://developer.pandora.com/)

### AdsWizz Domain API

The AdsWizz Domain API is a programmatic audio advertising platform enabling dynamic ad insertion, campaign management, and audience targeting across streaming radio, podcasts, and digital audio. AdsWizz is a SiriusXM company powering AudioID for listener identity and contextual targeting.

**Human URL:** https://docs.adswizz.com/domain-api/v8/

#### Properties

- [Documentation](https://docs.adswizz.com/domain-api/v8/)

### AdsWizz SDK

The AdsWizz SDK provides mobile and web integration for VAST-compliant audio advertising with companion banner support for iOS, Android, and Web platforms.

**Human URL:** https://docs.sdk.adswizz.com/

#### Properties

- [Documentation](https://docs.sdk.adswizz.com/)

## JSON Schemas

- [Track Schema](json-schema/sirius-xm-track-schema.json)
- [Station Schema](json-schema/sirius-xm-station-schema.json)

## JSON Structures

- [Playback Response Structure](json-structure/sirius-xm-playback-structure.json)

## JSON-LD

- [Sirius XM Context](json-ld/sirius-xm-context.jsonld)

## Examples

- [Pandora GraphQL Search](examples/sirius-xm-pandora-search-example.json)

## Vocabulary

- [Sirius XM Vocabulary](vocabulary/sirius-xm-vocabulary.yml)

## Common Links

- **Website:** https://www.siriusxm.com/
- **Pandora Developer Portal:** https://developer.pandora.com/
- **Advertising Platform:** https://www.siriusxmmedia.com/
- **AdsWizz:** https://www.adswizz.com/
- **AdsWizz Docs:** https://docs.adswizz.com/
- **Blog:** https://www.siriusxm.com/blog/
- **GitHub:** https://github.com/SiriusXM
- **Investor Relations:** https://investor.siriusxm.com/
- **Terms of Service:** https://www.siriusxm.com/terms
- **Privacy Policy:** https://www.siriusxm.com/privacy

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
