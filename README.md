# US Bureau of Labor Statistics (us-bureau-of-labor-statistics)

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

The US Bureau of Labor Statistics (BLS) is the principal federal agency responsible for measuring labor market activity, working conditions, price changes, and productivity in the US economy. BLS provides a Public Data API that enables developers to retrieve published historical time series data covering employment, unemployment, inflation, wages, productivity, and occupational statistics across all BLS programs. The API supports both unauthenticated access (v1) and registered access with higher limits (v2), returning data in JSON format for integration into applications, research tools, and economic dashboards.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/us-bureau-of-labor-statistics/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/us-bureau-of-labor-statistics/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Federal Government
- Labor Statistics
- Economic Data
- Open Data

## Timestamps

- **Created:** 2025-02-09
- **Modified:** 2026-05-19

## APIs

### BLS Public Data API

The BLS Public Data API allows developers to programmatically retrieve published historical time series data from all BLS surveys. Version 1 is open without registration; Version 2 requires a free API key and provides higher query limits (500 daily, up to 50 series per request, 20 years of data). The API covers Consumer Price Index (CPI), employment and unemployment statistics, wages, productivity, industry employment, and occupational statistics. Data is returned in JSON format.

- **Human URL:** [https://www.bls.gov/developers/home.htm](https://www.bls.gov/developers/home.htm)
- **Base URL:** `https://api.bls.gov/publicAPI/v2`

#### Tags

- Labor Statistics
- Employment
- Unemployment
- Consumer Price Index
- Economic Data
- Time Series
- Open Data

#### Properties

- [Documentation](https://www.bls.gov/developers/home.htm)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/us-bureau-of-labor-statistics/refs/heads/main/openapi/bls-public-data-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Registration](https://data.bls.gov/registrationEngine/)
- [Terms of Service](https://www.bls.gov/developers/termsOfService.htm)
- [Data A P I](https://api.bls.gov/publicAPI/v2/timeseries/data/)
- [Postman Collection](collections/bls-public-data-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bls-public-data-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/bureau-of-labor-statistics)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
