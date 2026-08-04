# US Department of Defense (us-department-of-defense)

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

The US Department of Defense is responsible for providing the military forces needed to deter war and protect the security of the United States. This includes overseeing the Army, Navy, Marine Corps, and Air Force, as well as coordinating with other defense agencies and organizations. The Department of Defense also plays a critical role in developing military strategies, acquiring and maintaining weapons and equipment, and ensuring the readiness and effectiveness of the armed forces. The DoD's data strategy initiatives have led to the publication of multiple public APIs including the USACE Corps Water Management System API, Lock Performance Monitoring System, and the DoD open data portal.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/us-department-of-defense/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/us-department-of-defense/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Federal Government
- Defense
- Military
- Water Management
- Waterways
- Open Data

## Timestamps

- **Created:** 2024-12-03
- **Modified:** 2026-05-19

## APIs

### USACE Corps Water Management System Data API

The USACE Corps Water Management System Data API (CDA) is a REST service providing programmatic access to USACE water management data including time series measurements, monitoring locations, rating curves, reservoir levels, and operational data across Army Corps of Engineers projects. Supports both public read access and authenticated write operations.

- **Human URL:** [https://cwms-data.usace.army.mil/cwms-data/](https://cwms-data.usace.army.mil/cwms-data/)

#### Tags

- Water Management
- Hydrology
- Army Corps of Engineers
- Federal Government

#### Properties

- [Documentation](https://cwms-data.usace.army.mil/cwms-data/)
- [Swagger U I](https://cwms-data.usace.army.mil/cwms-data/swagger-ui.html)
- [Documentation](https://cwms-data-api.readthedocs.io/latest/)
- [Git Hub](https://github.com/USACE/cwms-data-api)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/us-department-of-defense/refs/heads/main/openapi/usace-cwms-data-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/usace-cwms-data-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usace-cwms-data-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### USACE Lock Performance Monitoring System API

The USACE Lock Performance Monitoring System (LPMS) API provides data on inland waterway lock operations across the US Army Corps of Engineers lock system. Endpoints return XML data for lock queue reports (past 24 hours), tonnage reports, and traffic reports (past 30 days). Tracks vessel traffic through 192 commercially active locks on US inland waterways.

- **Human URL:** [https://corpslocks.usace.army.mil/lpwb/f](https://corpslocks.usace.army.mil/lpwb/f)

#### Tags

- Waterways
- Navigation
- Locks
- Federal Government

#### Properties

- [Documentation](https://corpslocks.usace.army.mil/lpwb/f)
- [Data Catalog](https://catalog.data.gov/dataset/corps-locks)
- [Postman Collection](collections/usace-cwms-data-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usace-cwms-data-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### DoD Data Portal

The Department of Defense Data Portal features APIs enabling access to DoD open data across military branches, agencies, and programs. The portal surfaces selected APIs from the DoD's data strategy initiative to make defense data more accessible through reusable APIs.

- **Human URL:** [https://data.defense.gov/Featured-API/](https://data.defense.gov/Featured-API/)

#### Tags

- Open Data
- Defense
- Federal Government

#### Properties

- [Documentation](https://data.defense.gov/Featured-API/)
- [Portal](https://data.defense.gov/)
- [Postman Collection](collections/usace-cwms-data-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usace-cwms-data-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### DoD Open Data Platform

The Department of Defense Open Data Platform (data.mil) provides access to unclassified DoD datasets and data services supporting defense research, policy analysis, and public accountability.

- **Human URL:** [https://www.data.mil/](https://www.data.mil/)

#### Tags

- Open Data
- Defense
- Datasets
- Federal Government

#### Properties

- [Portal](https://www.data.mil/)
- [Postman Collection](collections/usace-cwms-data-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usace-cwms-data-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/united-states-department-of-defense)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
