# US Bureau of Labor Statistics

The US Bureau of Labor Statistics (BLS) is the principal federal agency responsible for measuring labor market activity, working conditions, price changes, and productivity in the US economy. BLS provides a Public Data API that enables developers to retrieve published historical time series data covering employment, unemployment, inflation, wages, productivity, and occupational statistics across all BLS programs.

**Human URL:** [https://www.bls.gov/developers/home.htm](https://www.bls.gov/developers/home.htm)

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
- **Modified:** 2026-05-03

## APIs

### BLS Public Data API

The BLS Public Data API provides programmatic access to all BLS statistical time series. Version 1 is open without registration; Version 2 requires a free API key and offers higher limits (500 daily queries, 50 series per request, 20 years of data).

- **Base URL:** `https://api.bls.gov/publicAPI/v2`
- **Documentation:** [https://www.bls.gov/developers/home.htm](https://www.bls.gov/developers/home.htm)
- **Registration:** [https://data.bls.gov/registrationEngine/](https://data.bls.gov/registrationEngine/)
- **Terms of Service:** [https://www.bls.gov/developers/termsOfService.htm](https://www.bls.gov/developers/termsOfService.htm)

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
- [OpenAPI](openapi/bls-public-data-api-openapi.yml)
- [Registration](https://data.bls.gov/registrationEngine/)
- [TermsOfService](https://www.bls.gov/developers/termsOfService.htm)

## Artifacts

### OpenAPI Specifications

| Spec | Description |
|------|-------------|
| [bls-public-data-api-openapi.yml](openapi/bls-public-data-api-openapi.yml) | BLS Public Data API v2 - time series, surveys, and popular series |

### JSON Schemas

| Schema | Description |
|--------|-------------|
| [bls-time-series-schema.json](json-schema/bls-time-series-schema.json) | Schema for BLS time series data including data points, catalog metadata, and calculations |

### JSON Structures

| Structure | Description |
|-----------|-------------|
| [bls-time-series-structure.json](json-structure/bls-time-series-structure.json) | Hierarchical structure documentation for BLS time series API responses |

### JSON-LD Contexts

| Context | Description |
|---------|-------------|
| [us-bureau-of-labor-statistics-context.jsonld](json-ld/us-bureau-of-labor-statistics-context.jsonld) | Linked data context mapping BLS concepts to schema.org, DCAT, and Dublin Core |

### Examples

| Example | Description |
|---------|-------------|
| [bls-get-unemployment-rate-example.json](examples/bls-get-unemployment-rate-example.json) | POST request to retrieve national unemployment rate time series with calculations |
| [bls-list-surveys-example.json](examples/bls-list-surveys-example.json) | GET request to list all BLS survey programs |

### Spectral Rules

| Ruleset | Description |
|---------|-------------|
| [bls-public-data-api-rules.yml](rules/bls-public-data-api-rules.yml) | Spectral linting rules enforcing BLS API conventions |

### Naftiko Capabilities

**Shared Definitions:**

| File | Description |
|------|-------------|
| [capabilities/shared/bls-public-data-api.yaml](capabilities/shared/bls-public-data-api.yaml) | Shared capability definition for the BLS Public Data API |

**Workflow Capabilities:**

| Capability | APIs | Description |
|-----------|------|-------------|
| [capabilities/labor-statistics-data.yaml](capabilities/labor-statistics-data.yaml) | BLS Public Data API | Unified access to BLS labor statistics including unemployment, CPI, wages, and occupational data |

### Vocabulary

| File | Description |
|------|-------------|
| [us-bureau-of-labor-statistics-vocabulary.yml](vocabulary/us-bureau-of-labor-statistics-vocabulary.yml) | Domain vocabulary covering BLS concepts, survey programs, economic indicators, and data terminology |

## Key Data Domains

- **Employment & Unemployment** — National, state, metro, and demographic unemployment rates (CPS/LN series)
- **Consumer Price Index** — CPI-U and CPI-W inflation measures (CU/CW series)
- **Payroll Employment** — Nonfarm payroll employment and earnings by industry (CES/CE series)
- **Wages & Compensation** — Employment cost index, occupational wages (OE, EN series)
- **Productivity** — Labor productivity and costs by sector (PR series)
- **Job Openings** — JOLTS data on job openings, hires, and separations (JT series)
- **Producer Prices** — Producer price indexes by commodity and industry (PC series)

## Common Series IDs

| Series ID | Description |
|-----------|-------------|
| `LNS14000000` | Unemployment Rate (Seasonally Adjusted) |
| `CUUR0000SA0` | CPI-U All Items (Not Seasonally Adjusted) |
| `CES0000000001` | Total Nonfarm Employment (Seasonally Adjusted) |
| `CES0500000003` | Average Hourly Earnings, Private |
| `LNS11300000` | Labor Force Participation Rate |
| `JTS000000000000000JOR` | Job Openings Rate, Total Nonfarm |

## Maintainers

**Kin Lane** — [kin@apievangelist.com](mailto:kin@apievangelist.com)
