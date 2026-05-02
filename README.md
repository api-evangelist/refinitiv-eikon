# Refinitiv Eikon

Refinitiv Eikon provides financial professionals with access to real-time market data, news, analytics, and trading capabilities. The Eikon Data API allows programmatic access to financial data including prices, fundamentals, reference data, and time series. Eikon was withdrawn from the LSEG product line on June 30, 2025, and has been succeeded by LSEG Workspace.

**Human URL:** [https://developers.lseg.com/en/api-catalog](https://developers.lseg.com/en/api-catalog)

**Developer Portal:** [https://developers.lseg.com](https://developers.lseg.com)

## Tags

- Financial Data
- Market Data
- Analytics
- Real-Time Data
- Financial News
- Trading
- ESG

## APIs

### Eikon Data API
Python and R library for programmatic access to Refinitiv Eikon data including pricing, fundamentals, time series, news, and symbology.

- [Documentation](https://developers.lseg.com/en/api-catalog/eikon/eikon-data-api/documentation)

### Refinitiv Data Platform APIs
RESTful APIs for pricing, ESG, news, research, streaming, and alternative data.

- [Documentation](https://developers.lseg.com/en/api-catalog/refinitiv-data-platform/refinitiv-data-platform-apis/documentation)
- [OpenAPI](openapi/refinitiv-eikon-data-platform-openapi.yml)

### LSEG DataScope Select REST API
Bulk data extraction platform for prices, corporate actions, reference data, and historical data.

- [Documentation](https://developers.lseg.com/en/api-catalog/datascope-select/datascope-select-rest-api/documentation)
- [OpenAPI](openapi/refinitiv-eikon-datascope-select-openapi.yml)

### LSEG Tick History REST API
Historical tick-level market data including time-and-sales, intraday bars, and market depth.

- [Documentation](https://developers.lseg.com/en/api-catalog/refinitiv-tick-history/refinitiv-tick-history-rth-rest-api/documentation)
- [OpenAPI](openapi/refinitiv-eikon-tick-history-openapi.yml)

### Refinitiv Data Library for Python
Python library for streaming and non-streaming financial data access.

- [Documentation](https://developers.lseg.com/en/api-catalog/refinitiv-data-platform/refinitiv-data-library-for-python/documentation)

### World-Check One API
Entity screening against the World-Check risk intelligence database for KYC and AML workflows.

- [Documentation](https://developers.lseg.com/en/api-catalog/customer-and-third-party-screening/world-check-one-api/documentation)

## Artifacts

### OpenAPI Specifications

| Specification | Description |
|---------------|-------------|
| [Data Platform API](openapi/refinitiv-eikon-data-platform-openapi.yml) | RESTful API for pricing, ESG, news, symbology, and search |
| [DataScope Select API](openapi/refinitiv-eikon-datascope-select-openapi.yml) | Bulk data extraction platform |
| [Tick History API](openapi/refinitiv-eikon-tick-history-openapi.yml) | Historical tick-level market data |

### Rules

| Ruleset | Description |
|---------|-------------|
| [Refinitiv Eikon Rules](rules/refinitiv-eikon-rules.yml) | Spectral ruleset enforcing Refinitiv Eikon API conventions |

### Capabilities

| Capability | Description |
|------------|-------------|
| [Financial Data Research](capabilities/financial-data-research.yaml) | Unified capability for pricing, ESG, news, symbology research |
| [Data Extraction](capabilities/data-extraction.yaml) | Bulk data extraction via DataScope Select and Tick History |

**Shared Definitions:**
- [Data Platform](capabilities/shared/data-platform.yaml)
- [DataScope Select](capabilities/shared/datascope-select.yaml)
- [Tick History](capabilities/shared/tick-history.yaml)

### JSON Schema

| Schema | Description |
|--------|-------------|
| [Instrument Schema](json-schema/refinitiv-eikon-instrument-schema.json) | Financial instrument with RIC, ISIN, CUSIP, PermID, and pricing |
| [ESG Score Schema](json-schema/refinitiv-eikon-esg-schema.json) | ESG pillar scores and measures |

### JSON Structure

| Structure | Description |
|-----------|-------------|
| [Data Platform Structure](json-structure/refinitiv-eikon-data-platform-structure.json) | Structural documentation for all API endpoints and response shapes |

### JSON-LD

| Context | Description |
|---------|-------------|
| [Refinitiv Eikon Context](json-ld/refinitiv-eikon-context.jsonld) | JSON-LD context for financial instrument and ESG data |

### Examples

| Example | Description |
|---------|-------------|
| [Get Interday Pricing](examples/refinitiv-eikon-get-interday-pricing-example.json) | OHLCV pricing history request/response |
| [Get ESG Scores](examples/refinitiv-eikon-get-esg-scores-example.json) | ESG score retrieval for multiple instruments |

### Vocabulary

| Vocabulary | Description |
|------------|-------------|
| [Refinitiv Eikon Vocabulary](vocabulary/refinitiv-eikon-vocabulary.yml) | Domain vocabulary for financial data, identifiers, and Refinitiv-specific terms |

## Common Properties

- [Developer Portal](https://developers.lseg.com)
- [Community](https://community.developers.refinitiv.com/)
- [Blog](https://medium.com/lseg-developer-community)
- [API Playground](https://apidocs.refinitiv.com/Apps/ApiDocs)
- [Status](https://status.refinitiv.com/)
- [GitHub Organization](https://github.com/LSEG-API-Samples)
- [Terms of Service](https://www.refinitiv.com/en/policies/terms-of-use)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
