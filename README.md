# Transit (transit)

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
