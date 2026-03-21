# PlanetScale (planetscale)
PlanetScale is a serverless MySQL database platform built on Vitess that offers branching, non-blocking schema changes, and horizontal scaling. Their developer platform provides a REST API, OAuth integration, a JavaScript serverless driver, and a CLI for managing databases programmatically and integrating into modern development workflows.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/planetscale/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Databases, MySQL, Serverless, Cloud, Branching, Developer Tools

## Timestamps

- **Created:** 2025-03-04
- **Modified:** 2026-03-20

## APIs

### PlanetScale Platform API
The PlanetScale Platform API provides programmatic access to manage PlanetScale serverless MySQL databases. It allows developers to create and delete database branches, manage deploy requests, automate password and connection string management, and integrate PlanetScale into CI/CD pipelines and infrastructure-as-code workflows. The API supports authentication via service tokens and OAuth, and its base URL is https://api.planetscale.com/v1 with an OpenAPI 3.0 specification available for download.

**Human URL:** [https://api-docs.planetscale.com/reference/getting-started-with-planetscale-api](https://api-docs.planetscale.com/reference/getting-started-with-planetscale-api)


#### Tags:

 - Databases, MySQL, Serverless, Branching, Deploy Requests, Cloud

#### Properties

- [Documentation](https://api-docs.planetscale.com/reference/getting-started-with-planetscale-api)
- [OpenAPI](openapi/planetscale-platform-api-openapi.yml)
- [AsyncAPI](asyncapi/planetscale-webhooks-asyncapi.yml)

### PlanetScale OAuth
PlanetScale OAuth allows developers to create OAuth applications that can access users' PlanetScale accounts on their behalf. The implementation supports the Authorization Code grant type, enabling third-party applications to authenticate users and obtain delegated access to PlanetScale resources. This is particularly useful for building integrations and tools that need to interact with organization-level PlanetScale endpoints on behalf of multiple users.

**Human URL:** [https://planetscale.com/docs/api/planetscale-api-oauth-applications](https://planetscale.com/docs/api/planetscale-api-oauth-applications)


#### Tags:

 - OAuth, Authentication, Authorization, Applications

#### Properties

- [Documentation](https://planetscale.com/docs/api/planetscale-api-oauth-applications)

### PlanetScale Serverless Driver for JavaScript
The PlanetScale Serverless Driver for JavaScript is a Fetch API-compatible database driver designed for serverless and edge compute platforms such as Cloudflare Workers, Vercel Edge Functions, and Netlify Edge Functions. It enables developers to query PlanetScale databases over HTTP connections, bypassing the TCP restrictions common in edge environments. The driver is available as the @planetscale/database npm package and provides features like TLS 1.3, HTTP/2 connection multiplexing, protocol compression, and global routing for reduced latency.

**Human URL:** [https://planetscale.com/docs/tutorials/using-the-serverless-driver](https://planetscale.com/docs/tutorials/using-the-serverless-driver)


#### Tags:

 - JavaScript, Serverless, Edge Computing, SDK, Driver, MySQL

#### Properties

- [Documentation](https://planetscale.com/docs/tutorials/using-the-serverless-driver)

### PlanetScale CLI
The PlanetScale CLI (pscale) is a command-line tool that brings PlanetScale database management to the terminal. It allows developers to create, delete, and list databases and branches, open interactive MySQL shells for database branches, and manage deploy requests directly from the command line. The CLI is available via Homebrew and as a downloadable binary, and includes a Model Context Protocol (MCP) server that provides AI tools with direct access to PlanetScale databases.

**Human URL:** [https://planetscale.com/docs/reference/planetscale-cli](https://planetscale.com/docs/reference/planetscale-cli)


#### Tags:

 - CLI, Command Line, Developer Tools, Database Management

#### Properties

- [Documentation](https://planetscale.com/docs/reference/planetscale-cli)

## Common Properties

- [Portal](https://planetscale.com/docs)
- [Blog](https://planetscale.com/blog)
- [Login](https://app.planetscale.com/sign-in)
- [Sign Up](https://app.planetscale.com/sign-up)
- [Pricing](https://planetscale.com/pricing)
- [Support](https://support.planetscale.com)
- [Status](https://planetscalestatus.com)
- [GitHub](https://github.com/planetscale)
- [TermsOfService](https://planetscale.com/legal/tos)
- [PrivacyPolicy](https://planetscale.com/legal/privacy)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
