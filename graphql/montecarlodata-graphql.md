# Monte Carlo Data GraphQL API

Monte Carlo Data exposes a comprehensive GraphQL API that powers the full Monte Carlo data observability platform. The API provides programmatic access to all platform capabilities — including data monitors, incidents, field health metrics, data lineage, table and warehouse asset management, domain organization, and AI-assisted observability. With over 600 query operations and 560+ mutations, the API enables developers to automate monitoring configuration, bulk-manage data quality rules, integrate with external tools, and push custom metadata from sources that cannot be reached through Monte Carlo's standard pull-based collection.

The API is authenticated using API key credentials (key ID and token) issued from the Monte Carlo account settings. All requests are sent as HTTP POST to the single GraphQL endpoint. Monte Carlo also provides a Python SDK (pycarlo) that wraps the GraphQL API, a CLI for common operations, and a Postman collection for exploration. The API supports Relay-style cursor-based pagination across connection types and covers integrations with Snowflake, BigQuery, Redshift, Databricks, dbt, Airflow, Looker, Tableau, Jira, PagerDuty, and many other data stack tools.

Key domain areas include: monitors (freshness, volume, schema change, custom SQL, field quality, comparison, and metric monitors), alerts and incidents with triage workflows, data lineage nodes and edges, catalog asset metadata, account and authorization management, integration connections, AI agent observability, data products, and the Push Ingest API for custom metadata ingestion. The schema includes 2,511 named types covering objects, enums, inputs, and connection/edge types following the Relay pagination specification.

**Endpoint:** https://api.getmontecarlo.com/graphql

**Documentation:** https://docs.getmontecarlo.com/docs/api

**References:**

- Documentation: https://docs.getmontecarlo.com/docs/api
- GettingStarted: https://docs.getmontecarlo.com/docs/developer-resources
- Reference: https://apidocs.getmontecarlo.com
- APIExplorer: https://getmontecarlo.com/graphiql
- SDK: https://github.com/monte-carlo-data/monte-carlo-python-sdk-examples
- Postman: https://github.com/monte-carlo-data/mc-postman
