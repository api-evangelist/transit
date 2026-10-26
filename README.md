# Transit (transit)

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

Transit ("The world's most accurate transit app") provides real-time public transit data, multimodal trip planning, and shared mobility across 1,000+ cities including New York, Paris, London, and Montreal, partnering with 180+ transit agencies. The platform aggregates trains, buses, bikes, scooters, and carshares with crowdsourced GO real-time signals, ships a freemium partner API (5 calls/minute, 1,500 calls/month), and monetizes consumers via the Transit Royale subscription ($2/month billed annually).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/transit/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/transit/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Public Transit
- Real-Time
- Trip Planning
- Multimodal
- GTFS
- GOFS
- Mobility
- Shared Mobility

## Timestamps

- **Created:** 2025-05-02
- **Modified:** 2026-05-23

## APIs

### Transit API

The Transit API delivers real-time transit departures, wheelchair accessibility details, service alerts, bike/scooter/carshare availability, and multimodal trip planning across 1,000+ cities in 25 countries. Access is gated by a request form; approved keys get 5 calls per minute and 1,500 calls per month free, with higher volumes negotiated through the partnerships team.

- **Human URL:** [https://transitapp.com/apis](https://transitapp.com/apis)
- **Base URL:** `https://api-doc.transitapp.com`

#### Tags

- Public Transit
- Real-Time
- Trip Planning
- GTFS
- Multimodal
- Mobility
- Shared Mobility

#### Properties

- [Documentation](https://api-doc.transitapp.com/)
- [OpenAPI](openapi/transit-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/transit.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/transit.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/transit-stop-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/transit-departure-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/transit-stop-structure.json)
- [JSON-LD](json-ld/transit-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/transit-rules.yml)
- [Vocabulary](vocabulary/transit-vocabulary.yml)
- [Plans](plans/transit-plans-pricing.yml)
- [Rate Limits](rate-limits/transit-rate-limits.yml)
- [Fin Ops](finops/transit-finops.yml)
- [Sign Up](https://docs.google.com/forms/d/e/1FAIpQLScZbUsb1G1gRzIkEQo4FuuAbfzQbldTvu6-62j_pSRWPtKZiA/viewform)
- [G T F S Guidelines](https://resources.transitapp.com/article/458-guidelines-for-producing-gtfs-static-data-for-transit)

### Transit URL Scheme

Deep-link URL scheme for launching the Transit mobile app from partner apps and websites. Supports directions and nearby-routes hand-offs without requiring an API key.

- **Human URL:** [https://transitapp.com/apis](https://transitapp.com/apis)
- **Base URL:** `transit://`

#### Tags

- Deep Linking
- Mobile
- URL Scheme
- Public Transit

#### Properties

- [Documentation](https://transitapp.com/apis)
- [Postman Collection](collections/transit.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/transit.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://transitapp.com/)
- [Documentation](https://transitapp.com/apis)
- [A P I Documentation](https://api-doc.transitapp.com/)
- [Git Hub](https://github.com/TransitApp)
- [Blog](https://blog.transitapp.com/)
- [Blog Feed](https://blog.transitapp.com/feed/)
- [Support](https://help.transitapp.com/)
- [Careers](https://transitapp.com/careers)
- [Press](https://transitapp.com/press)
- [Pricing](https://transitapp.com/apis)
- [Sign Up](https://docs.google.com/forms/d/e/1FAIpQLScZbUsb1G1gRzIkEQo4FuuAbfzQbldTvu6-62j_pSRWPtKZiA/viewform)
- [Contact Sales](mailto:partners+website@transit.app)
- [Contact General](mailto:info@transit.app)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
