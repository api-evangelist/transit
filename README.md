# Transit

Transit ("The world's most accurate transit app") provides real-time public transit data, multimodal trip planning, and shared mobility across 1,000+ cities including New York, Paris, London, and Montreal, partnering with 180+ transit agencies. The platform aggregates trains, buses, bikes, scooters, and carshares with crowdsourced GO real-time signals, ships a freemium partner API (5 calls/minute, 1,500 calls/month), and monetizes consumers via the Transit Royale subscription ($2/month billed annually).

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/transit/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

Public Transit, Real-Time, Trip Planning, Multimodal, GTFS, GOFS, Mobility, Shared Mobility

## Timestamps

- **Created:** 2025-05-02
- **Modified:** 2026-05-23

## APIs

### Transit API
Real-time transit departures, wheelchair accessibility details, service alerts, bike/scooter/carshare availability, and multimodal trip planning across 1,000+ cities. Access is gated by a request form; free tier capped at 5 calls/minute and 1,500 calls/month.

**Human URL:** [https://transitapp.com/apis](https://transitapp.com/apis)

**Base URL:** `https://api-doc.transitapp.com`

#### Properties

- [Documentation](https://api-doc.transitapp.com/)
- [OpenAPI](openapi/transit-openapi.yml)
- [JSON Schema - Stop](json-schema/transit-stop-schema.json)
- [JSON Schema - Departure](json-schema/transit-departure-schema.json)
- [JSON Structure](json-structure/transit-stop-structure.json)
- [JSON-LD Context](json-ld/transit-context.jsonld)
- [Spectral Rules](rules/transit-rules.yml)
- [Naftiko Capabilities](capabilities/real-time-transit.yaml)
- [Vocabulary](vocabulary/transit-vocabulary.yml)
- [Plans & Pricing](plans/transit-plans-pricing.yml)
- [Rate Limits](rate-limits/transit-rate-limits.yml)
- [FinOps](finops/transit-finops.yml)
- [Sign-up Form](https://docs.google.com/forms/d/e/1FAIpQLScZbUsb1G1gRzIkEQo4FuuAbfzQbldTvu6-62j_pSRWPtKZiA/viewform)
- [GTFS Guidelines](https://resources.transitapp.com/article/458-guidelines-for-producing-gtfs-static-data-for-transit)

### Transit URL Scheme
Deep-link URL scheme (`transit://`) for launching the Transit mobile app from partner apps and websites. Supports directions and nearby-routes hand-offs without an API key.

## OpenAPI Specifications

| API | File |
|---|---|
| Transit API | [openapi/transit-openapi.yml](openapi/transit-openapi.yml) |

## Capabilities

### Workflow Capabilities

| Workflow | Description |
|---|---|
| [Real-Time Transit](capabilities/real-time-transit.yaml) | Departures, trip planning, alerts, and nearby vehicles for transit apps and signage |

### Shared Definitions

| API | File |
|---|---|
| [Transit](capabilities/shared/transit.yaml) | Core Transit API consumed definitions |

## Examples

| Example | Description |
|---|---|
| [Get Stop Departures](examples/transit-get-stop-departures-example.json) | Get real-time departures for a stop |
| [Plan Trip](examples/transit-plan-trip-example.json) | Plan a multimodal trip |

## Rules

| Ruleset | Description |
|---|---|
| [transit-rules.yml](rules/transit-rules.yml) | Spectral ruleset for Transit API conventions |

## JSON Schemas

| Schema | Description |
|---|---|
| [transit-stop-schema.json](json-schema/transit-stop-schema.json) | Transit stop |
| [transit-departure-schema.json](json-schema/transit-departure-schema.json) | Transit departure |

## JSON Structures

| Structure | Description |
|---|---|
| [transit-stop-structure.json](json-structure/transit-stop-structure.json) | Transit stop fields |

## JSON-LD

| Context | Description |
|---|---|
| [transit-context.jsonld](json-ld/transit-context.jsonld) | Linked data context (GTFS + schema.org) |

## Vocabulary

| Vocabulary | Description |
|---|---|
| [transit-vocabulary.yml](vocabulary/transit-vocabulary.yml) | Public transit and multimodal mobility terms |

## Plans, Rate Limits & FinOps

| Artifact | File |
|---|---|
| API Commons Plans 0.1 | [plans/transit-plans-pricing.yml](plans/transit-plans-pricing.yml) |
| API Commons Rate Limits 0.1 | [rate-limits/transit-rate-limits.yml](rate-limits/transit-rate-limits.yml) |
| FinOps Framework 1.0 / FOCUS 1.3 | [finops/transit-finops.yml](finops/transit-finops.yml) |

## GitHub Repositories

Transit's open-source surface centers on GTFS tooling and the GOFS on-demand specification. Twelve relevant repos are catalogued in `apis.yml` under `x-github-repos`. Notable ones:

| Repo | Language | Description |
|---|---|---|
| [gtfsNodeLib](https://github.com/TransitApp/gtfsNodeLib) | JavaScript | Node.js library for GTFS feeds |
| [Transit-TV](https://github.com/TransitApp/Transit-TV) | JavaScript | Big-screen departure display using the Transit API |
| [gtfs-fares-v2-validator](https://github.com/TransitApp/gtfs-fares-v2-validator) | Python | Validates GTFS fares-v2 datasets |
| [GTFS-blocks-to-transfers](https://github.com/TransitApp/GTFS-blocks-to-transfers) | Python | Converts GTFS blocks into trip-to-trip transfers |
| [GTFS-flex-to-GOFS](https://github.com/TransitApp/GTFS-flex-to-GOFS) | Python | Converts GTFS-Flex to GOFS-lite |
| [gtfs-realtime-bindings](https://github.com/TransitApp/gtfs-realtime-bindings) | JavaScript | Bindings for the GTFS-realtime protobuf spec |
| [transitfeed](https://github.com/TransitApp/transitfeed) | Python | Read/validate/write GTFS schedule feeds |

## Common Properties

- [Website](https://transitapp.com/)
- [Developer Documentation](https://transitapp.com/apis)
- [API Reference](https://api-doc.transitapp.com/)
- [GitHub](https://github.com/TransitApp)
- [Blog](https://blog.transitapp.com/) ([RSS](https://blog.transitapp.com/feed/))
- [Support](https://help.transitapp.com/)
- [Careers](https://transitapp.com/careers)
- [Press](https://transitapp.com/press)
- [Sign-up Form](https://docs.google.com/forms/d/e/1FAIpQLScZbUsb1G1gRzIkEQo4FuuAbfzQbldTvu6-62j_pSRWPtKZiA/viewform)
- Contact: partners+website@transit.app / info@transit.app

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
