# Sirius XM

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
