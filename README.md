# Tinybird

Tinybird is a real-time data platform that allows you to ingest, process, and expose data through low-latency, high-concurrency APIs. The platform supports real-time analytics at scale with a SQL-based transformation layer and instant REST API endpoint publishing.

**URL:** [https://raw.githubusercontent.com/api-evangelist/tinybird/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/tinybird/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

Analytics, Data, Real-Time, SQL, Streaming

## APIs

### Tinybird API

Tinybird provides a real-time data platform with comprehensive REST APIs for managing data sources, executing SQL queries, managing pipes and transformations, ingesting events, managing authentication tokens, monitoring jobs, and administering organizations and workspaces.

**Human URL:** [https://www.tinybird.co/docs/api-reference](https://www.tinybird.co/docs/api-reference)
**Base URL:** `https://api.tinybird.co`

#### Tags

Analytics, Data, Real-Time, SQL, Streaming

#### Properties

- [Documentation](https://www.tinybird.co/docs/api-reference)
- [OpenAPI](openapi/tinybird-openapi.yml)
- [Getting Started](https://www.tinybird.co/docs/get-started)
- [JSON Schema - Data Source](json-schema/tinybird-data-source-schema.json)
- [JSON Schema - Pipe](json-schema/tinybird-pipe-schema.json)
- [JSON Schema - Token](json-schema/tinybird-token-schema.json)
- [JSON Structure](json-structure/tinybird-data-source-structure.json)
- [JSON-LD Context](json-ld/tinybird-context.jsonld)
- [Spectral Rules](rules/tinybird-rules.yml)

## Features

- Real-time data ingestion via Events API
- SQL-based data transformation with Pipes
- Instant REST API endpoint publishing
- Multi-region deployment support
- Materialized views for query optimization
- Sink pipes for data export
- Token-based access control with scopes
- Job tracking for async operations
- Organization and workspace management
- Environment variables for pipeline configuration

## Use Cases

- Real-time analytics dashboards
- User-facing analytics APIs
- Event stream processing
- Log analytics and monitoring
- A/B testing and experimentation data
- Financial data processing
- IoT sensor data analytics

## Capabilities

### Shared Definitions

| API | File |
|---|---|
| Tinybird | [capabilities/shared/tinybird.yaml](capabilities/shared/tinybird.yaml) |

### Workflow Capabilities

| Workflow | File | APIs |
|---|---|---|
| Real-Time Analytics | [capabilities/real-time-analytics.yaml](capabilities/real-time-analytics.yaml) | Tinybird (10 tools) |

## Artifacts

| Type | File |
|---|---|
| OpenAPI | [tinybird-openapi.yml](openapi/tinybird-openapi.yml) |
| JSON Schema (Data Source) | [tinybird-data-source-schema.json](json-schema/tinybird-data-source-schema.json) |
| JSON Schema (Pipe) | [tinybird-pipe-schema.json](json-schema/tinybird-pipe-schema.json) |
| JSON Schema (Token) | [tinybird-token-schema.json](json-schema/tinybird-token-schema.json) |
| JSON Structure | [tinybird-data-source-structure.json](json-structure/tinybird-data-source-structure.json) |
| JSON-LD Context | [tinybird-context.jsonld](json-ld/tinybird-context.jsonld) |
| Spectral Rules | [tinybird-rules.yml](rules/tinybird-rules.yml) |
| Vocabulary | [tinybird-vocabulary.yml](vocabulary/tinybird-vocabulary.yml) |

## Examples

- [List Data Sources](examples/tinybird-list-data-sources-example.json)
- [Ingest Events](examples/tinybird-ingest-events-example.json)
- [Execute SQL Query](examples/tinybird-execute-sql-query-example.json)

## Integrations

- Kafka data ingestion
- DynamoDB connector
- S3 data sources
- Snowflake
- Confluent
- dbt transformations
- TypeScript SDK
- Python SDK

## Common Properties

- [Website](https://www.tinybird.co/)
- [Documentation](https://www.tinybird.co/docs/api-reference)
- [Getting Started](https://www.tinybird.co/docs/get-started)
- [Sign Up](https://www.tinybird.co/signup)
- [Blog](https://www.tinybird.co/blog)
- [GitHub Organization](https://github.com/tinybirdco)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
