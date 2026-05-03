# US Department of Defense

The US Department of Defense is responsible for providing the military forces needed to deter war and protect the security of the United States. This includes overseeing the Army, Navy, Marine Corps, and Air Force, as well as coordinating with other defense agencies and organizations. The Department of Defense also plays a critical role in developing military strategies, acquiring and maintaining weapons and equipment, and ensuring the readiness and effectiveness of the armed forces.

**URL:** [https://www.defense.gov](https://www.defense.gov)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

`Federal Government` `Defense` `Military` `Water Management` `Waterways` `Open Data`

## Timestamps

- **Created:** 2024-12-03
- **Modified:** 2026-05-03

## APIs

| API | Description |
|-----|-------------|
| [USACE CWMS Data API](https://cwms-data.usace.army.mil/cwms-data/) | Corps Water Management System - time series, locations, ratings, pools |
| [USACE Lock Performance Monitoring System](https://corpslocks.usace.army.mil/lpwb/f) | Inland waterway lock queue, tonnage, and traffic reports |
| [DoD Data Portal](https://data.defense.gov/Featured-API/) | Department of Defense featured APIs and open data |
| [DoD Open Data Platform](https://www.data.mil/) | Unclassified DoD datasets and data services |

## OpenAPI Specifications

| Spec | Description |
|------|-------------|
| [USACE CWMS Data API](openapi/usace-cwms-data-api-openapi.yml) | OpenAPI 3.0 spec for CWMS water management data |

## Spectral Rules

| Ruleset | Description |
|---------|-------------|
| [USACE CWMS Rules](rules/usace-cwms-data-api-rules.yml) | Spectral rules for CWMS Data API conventions |

## Naftiko Capabilities

### Workflow Capabilities

| Capability | Description |
|------------|-------------|
| [Water Management](capabilities/water-management.yaml) | USACE water management monitoring and operations |

### Shared API Definitions

| Shared Definition | Description |
|-------------------|-------------|
| [USACE CWMS Data API](capabilities/shared/usace-cwms-data-api.yaml) | Shared definition for CWMS Data API |

## JSON Schema

| Schema | Description |
|--------|-------------|
| [CWMS Time Series](json-schema/usace-cwms-timeseries-schema.json) | Schema for CWMS time series responses |

## JSON Structure

| Structure | Description |
|-----------|-------------|
| [CWMS Time Series Structure](json-structure/usace-cwms-timeseries-structure.json) | Field documentation for CWMS time series data |

## JSON-LD

| Context | Description |
|---------|-------------|
| [DoD Context](json-ld/us-department-of-defense-context.jsonld) | Linked data context for DoD/USACE water management |

## Examples

| Example | Description |
|---------|-------------|
| [Get Time Series Example](examples/usace-cwms-get-timeseries-example.json) | Example CWMS time series response |

## Vocabulary

| Vocabulary | Description |
|------------|-------------|
| [DoD Vocabulary](vocabulary/us-department-of-defense-vocabulary.yml) | Domain vocabulary for DoD water management |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
