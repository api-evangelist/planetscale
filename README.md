# planetscale (planetscale)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
