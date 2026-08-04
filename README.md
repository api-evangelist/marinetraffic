# MarineTraffic (marinetraffic)

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

MarineTraffic, a Kpler company, is a global provider of vessel tracking and maritime intelligence data. The platform offers AIS-based real-time vessel positions, port calls, predictive ETAs, historical voyage data, and ship registry information used for fleet monitoring, port operations, and supply chain visibility.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/marinetraffic/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/marinetraffic/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- AIS
- Maritime
- Shipping
- Vessel Tracking

## Timestamps

- **Created:** 2026-03-18
- **Modified:** 2026-05-19

## APIs

### MarineTraffic AIS Vessel Tracking API

MarineTraffic AIS API provides real-time vessel position data from over 13,000 AIS receivers globally. Returns vessel positions, speeds, headings, and voyage information for fleet monitoring, port operations, and supply chain visibility.

- **Human URL:** [https://www.kpler.com/product/maritime/data-services](https://www.kpler.com/product/maritime/data-services)
- **Base URL:** `https://services.marinetraffic.com/api`

#### Tags

- AIS
- Maritime
- Real-Time
- Shipping
- Vessel Tracking

#### Properties

- [Documentation](https://www.kpler.com/product/maritime/data-services)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/marinetraffic/refs/heads/main/openapi/marinetraffic-ais-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/marinetraffic/refs/heads/main/json-schema/marinetraffic-vessel-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/marinetraffic/refs/heads/main/json-ld/marinetraffic-context.jsonld)
- [Postman Collection](collections/marinetraffic-ais.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/marinetraffic-ais.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MarineTraffic Real-time Events API

MarineTraffic Real-time Events API delivers live updates on port calls, bunkering operations, ship-to-ship transfers, and other maritime events as they occur.

- **Human URL:** [https://www.kpler.com/product/maritime/data-services](https://www.kpler.com/product/maritime/data-services)
- **Base URL:** `https://services.marinetraffic.com/api`

#### Tags

- Bunkering
- Events
- Maritime
- Port Calls

#### Properties

- [Documentation](https://www.kpler.com/product/maritime/data-services)
- [Postman Collection](collections/marinetraffic-ais.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/marinetraffic-ais.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MarineTraffic Predictive Events API

MarineTraffic Predictive Events API delivers predicted destinations, estimated time of arrivals (ETAs), and voyage forecasts using AI and AIS data analysis.

- **Human URL:** [https://www.kpler.com/product/maritime/data-services](https://www.kpler.com/product/maritime/data-services)
- **Base URL:** `https://services.marinetraffic.com/api`

#### Tags

- ETA
- Maritime
- Predictions
- Voyage Forecasting

#### Properties

- [Documentation](https://www.kpler.com/product/maritime/data-services)
- [Postman Collection](collections/marinetraffic-ais.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/marinetraffic-ais.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MarineTraffic Past Events API

MarineTraffic Past Events API provides access to historical vessel movements and events, enabling retrospective analysis of shipping patterns, port call history, and voyage records.

- **Human URL:** [https://www.kpler.com/product/maritime/data-services](https://www.kpler.com/product/maritime/data-services)
- **Base URL:** `https://services.marinetraffic.com/api`

#### Tags

- Historical
- Maritime
- Vessel Movements

#### Properties

- [Documentation](https://www.kpler.com/product/maritime/data-services)
- [Postman Collection](collections/marinetraffic-ais.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/marinetraffic-ais.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MarineTraffic Ship Database API

MarineTraffic Ship Database API provides detailed information on vessel characteristics, ownership, photos, vessel type, flag state, dimensions, and technical specifications for ships worldwide.

- **Human URL:** [https://www.kpler.com/product/maritime/data-services](https://www.kpler.com/product/maritime/data-services)
- **Base URL:** `https://services.marinetraffic.com/api`

#### Tags

- Maritime
- Ship Registry
- Vessel Data

#### Properties

- [Documentation](https://www.kpler.com/product/maritime/data-services)
- [Postman Collection](collections/marinetraffic-ais.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/marinetraffic-ais.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MarineTraffic AIS Vessel Tracking API

MarineTraffic provides AIS (Automatic Identification System) vessel tracking APIs delivering real-time vessel positions, speeds, headings, destinations, and ETAs. The REST API returns XML-formatted AIS data for fleet monitoring, port operations, and supply chain visibility.

- **Human URL:** [https://www.marinetraffic.com/en/ais-api-services](https://www.marinetraffic.com/en/ais-api-services)
- **Base URL:** `https://services.marinetraffic.com/api`

#### Tags

- AIS
- Maritime
- Shipping
- Vessel Tracking
- XML

#### Properties

- [Documentation](https://www.marinetraffic.com/en/ais-api-services)
- [Postman Collection](collections/marinetraffic-ais.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/marinetraffic-ais.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/marinetraffic)
- [LinkedIn](https://www.linkedin.com/company/marinetraffic)
- [Portal](https://www.kpler.com/product/maritime/data-services)
- [Documentation](https://developers.kpler.com/)
- [Terms of Service](https://www.kpler.com/company/terms-of-use)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/marinetraffic/refs/heads/main/openapi/marinetraffic-ais-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/marinetraffic/refs/heads/main/json-schema/marinetraffic-vessel-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/marinetraffic/refs/heads/main/json-ld/marinetraffic-context.jsonld)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
