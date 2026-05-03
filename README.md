# Transit

Transit provides real-time public transit data, trip planning, and multimodal mobility solutions across 900 cities in 25 countries. The platform aggregates data for trains, buses, bikes, scooters, and carshares, offering accurate real-time departure times and intuitive trip planning.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/transit/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

Public Transit, Real-Time, Trip Planning, Multimodal, GTFS, Mobility

## Timestamps

- **Created:** 2025-05-02
- **Modified:** 2026-05-03

## APIs

### Transit API
Real-time transit departures, wheelchair accessibility details, service alerts, bike and scooter availability, and multimodal trip planning across 900 cities in 25 countries.

**Human URL:** [https://transitapp.com/apis](https://transitapp.com/apis)

**Base URL:** `https://api-doc.transitapp.com`

#### Tags

Public Transit, Real-Time, Trip Planning, GTFS, Multimodal, Mobility

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

## Common Properties

- [Website](https://transitapp.com/)
- [Documentation](https://transitapp.com/apis)
- [GitHub](https://github.com/TransitApp)
- [Sign Up](https://transitapp.com/apis)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
