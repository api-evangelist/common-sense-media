# Common Sense Media (common-sense-media)

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

Common Sense Media is a nonprofit organization providing independent, age-rated reviews and ratings of movies, TV shows, books, video games, apps, podcasts, websites, and YouTube channels. The Common Sense Media Reviews API (v3) exposes this catalog via a partner-keyed REST surface hosted at api.commonsense.org/api/v3, with the partnership granted through Common Sense's Business Partner Program. The API is used by parenting apps, smart-TV guides, education platforms, and family-discovery products to surface age-appropriate guidance and the Common Sense Selection award.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/common-sense-media/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party
- **x-type:** company

## Tags

- Apps
- Books
- Media
- Movies
- Non-Profit
- Podcasts
- Ratings
- Reviews
- Television
- Video Games
- YouTube

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-04-26

## APIs

### Common Sense Media Reviews API
JSON REST API exposing Common Sense Media's reviews and ratings catalog. Each review includes recommended age, age-rating group, star rating, content grid (educational, message, role-model, diversity, violence, sex, language, consumerism, drugs), parents-need-to-know guidance, talking points, and product metadata. Clients filter by media type, age range, star range, character strengths, topics, genres, and the Common Sense Selection award.

**Base URL:** `https://api.commonsense.org/api/v3`

**Human URL:** [https://www.commonsensemedia.org/developers](https://www.commonsensemedia.org/developers)

#### Tags

- Apps, Books, Media, Movies, Ratings, Reviews, Television, Video Games

#### Properties

- [Documentation](https://www.commonsensemedia.org/developers/api-overview)
- [API v3 Overview](https://www.commonsensemedia.org/developers/api/v3)
- [Swagger UI](https://api.commonsense.org/docs/v3/)
- [Implementation Guide](https://www.commonsensemedia.org/developers/api/implementation)
- [OpenAPI](openapi/common-sense-media-reviews-api-openapi.yml)

## Common Properties

- [Website](https://www.commonsensemedia.org/)
- [Developer Center](https://www.commonsensemedia.org/developers)
- [API Overview](https://www.commonsensemedia.org/developers/api-overview)
- [API v3](https://www.commonsensemedia.org/developers/api/v3)
- [Swagger UI](https://api.commonsense.org/docs/v3/)
- [Implementation Guide](https://www.commonsensemedia.org/developers/api/implementation)
- [Partner Program Contact](https://commonsense.my.site.com/membersupport/s/contactsupport)
- [Privacy Policy](https://www.commonsensemedia.org/privacy-policy)
- [JSON-LD Context](json-ld/common-sense-media-context.jsonld)
- [Review JSON Schema](json-schema/common-sense-media-review-schema.json)
- [Spectral Ruleset](rules/common-sense-media-rules.yml)
- [Naftiko Capabilities](capabilities/common-sense-media-reviews-capabilities.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
