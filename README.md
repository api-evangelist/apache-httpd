# Apache HTTP Server (apache-httpd)

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
