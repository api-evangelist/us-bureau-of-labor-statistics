# US Bureau of Labor Statistics (us-bureau-of-labor-statistics)

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
