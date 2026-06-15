# planetscale (planetscale)

PlanetScale is a serverless MySQL database platform powered by Vitess, providing horizontal scaling, branching workflows, non-blocking schema changes, and other developer-friendly database features.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/planetscale/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/planetscale/refs/heads/main/apis.yml)

## Timestamps

- **Modified:** 2026-05-19

## APIs

### PlanetScale Platform API

The PlanetScale Platform API provides programmatic access to manage PlanetScale serverless MySQL databases. It allows developers to create and delete database branches, manage deploy requests, automate password and connection string management, and integrate PlanetScale into CI/CD pipelines and infrastructure-as-code workflows. The API supports authentication via service tokens and OAuth, and its base URL is https://api.planetscale.com/v1 with an OpenAPI 3.0 specification available for download.

- **Human URL:** [https://api-docs.planetscale.com/reference/getting-started-with-planetscale-api](https://api-docs.planetscale.com/reference/getting-started-with-planetscale-api)
- **Base URL:** `https://api.planetscale.com/v1`

#### Tags

- Branching
- Cloud
- Databases
- Deploy Requests
- MySQL
- Serverless

#### Properties

- [Documentation](https://api-docs.planetscale.com/reference/getting-started-with-planetscale-api)
- [OpenAPI](openapi/planetscale-platform-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/planetscale-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/planetscale-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/planetscale-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

### PlanetScale OAuth

PlanetScale OAuth allows developers to create OAuth applications that can access users' PlanetScale accounts on their behalf. The implementation supports the Authorization Code grant type, enabling third-party applications to authenticate users and obtain delegated access to PlanetScale resources. This is particularly useful for building integrations and tools that need to interact with organization-level PlanetScale endpoints on behalf of multiple users.

- **Human URL:** [https://planetscale.com/docs/api/planetscale-api-oauth-applications](https://planetscale.com/docs/api/planetscale-api-oauth-applications)
- **Base URL:** `https://api.planetscale.com`

#### Tags

- Applications
- Authentication
- Authorization
- OAuth

#### Properties

- [Documentation](https://planetscale.com/docs/api/planetscale-api-oauth-applications)
- [Postman Collection](collections/planetscale-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/planetscale-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PlanetScale Serverless Driver for JavaScript

The PlanetScale Serverless Driver for JavaScript is a Fetch API-compatible database driver designed for serverless and edge compute platforms such as Cloudflare Workers, Vercel Edge Functions, and Netlify Edge Functions. It enables developers to query PlanetScale databases over HTTP connections, bypassing the TCP restrictions common in edge environments.

- **Human URL:** [https://planetscale.com/docs/tutorials/using-the-serverless-driver](https://planetscale.com/docs/tutorials/using-the-serverless-driver)
- **Base URL:** `https://api.example.com`

#### Tags

- Driver
- Edge Computing
- JavaScript
- MySQL
- SDK
- Serverless

#### Properties

- [Documentation](https://planetscale.com/docs/tutorials/using-the-serverless-driver)
- [Postman Collection](collections/planetscale-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/planetscale-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PlanetScale CLI

The PlanetScale CLI (pscale) is a command-line tool that brings PlanetScale database management to the terminal. It allows developers to create, delete, and list databases and branches, open interactive MySQL shells for database branches, and manage deploy requests directly from the command line. The CLI is available via Homebrew and as a downloadable binary, and includes a Model Context Protocol (MCP) server that provides AI tools with direct access to PlanetScale databases.

- **Human URL:** [https://planetscale.com/docs/reference/planetscale-cli](https://planetscale.com/docs/reference/planetscale-cli)
- **Base URL:** `https://api.example.com`

#### Tags

- CLI
- Command Line
- Database Management
- Developer Tools

#### Properties

- [Documentation](https://planetscale.com/docs/reference/planetscale-cli)
- [Postman Collection](collections/planetscale-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/planetscale-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/planetscale)
- [LinkedIn](https://www.linkedin.com/company/planetscale)
- [JSON-LD](json-ld/planetscale-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/planetscale-database-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Features](undefined)
