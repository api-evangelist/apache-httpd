# Apache HTTP Server (apache-httpd)

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

Apache HTTP Server (httpd) is the world's most widely used web server software. It serves static and dynamic content, acts as a reverse proxy and load balancer, and exposes a mod_status monitoring API and balancer-manager management interface for operational visibility.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/apache-httpd/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-httpd/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Apache
- Load Balancer
- Open Source
- Proxy
- Reverse Proxy
- Web Server

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Apache HTTP Server Status API

Status and monitoring API for Apache HTTP Server (httpd) provided by mod_status, exposing server metrics, worker state, and load balancer information via HTTP endpoints.

- **Human URL:** [https://httpd.apache.org/docs/current/mod/mod_status.html](https://httpd.apache.org/docs/current/mod/mod_status.html)
- **Base URL:** `http://localhost:80`

#### Tags

- Balancer
- Metrics
- Monitoring
- REST
- Status

#### Properties

- [Documentation](https://httpd.apache.org/docs/current/mod/mod_status.html)
- [OpenAPI](openapi/apache-httpd-status-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apache-httpd-status.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-httpd-status.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/httpd-serverstatus-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/apache-httpd-status-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Apache HTTP Server Configuration Reference

Configuration directive reference for Apache HTTP Server covering VirtualHost, mod_ssl, mod_rewrite, mod_proxy, and all core directives for web server, proxy, and SSL configuration.

- **Human URL:** [https://httpd.apache.org/docs/current/mod/directives.html](https://httpd.apache.org/docs/current/mod/directives.html)

#### Tags

- Configuration
- Reference

#### Properties

- [Documentation](https://httpd.apache.org/docs/current/mod/directives.html)
- [Postman Collection](collections/apache-httpd-status.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-httpd-status.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Documentation](https://httpd.apache.org/docs/current/)
- [Getting Started](https://httpd.apache.org/docs/current/getting-started.html)
- [GitHub Organization](https://github.com/apache)
- [GitHub Repository](https://github.com/apache/httpd)
- [Spectral Rules](rules/apache-httpd-spectral-rules.yml)
- [Vocabulary](vocabulary/apache-httpd-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
