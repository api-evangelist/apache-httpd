# Apache HTTP Server (apache-httpd)
Apache HTTP Server (httpd) is the world's most widely used web server software. It serves static and dynamic content, acts as a reverse proxy and load balancer, and exposes a mod_status monitoring API and balancer-manager management interface for operational visibility.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/apache-httpd/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Apache, Load Balancer, Open Source, Proxy, Reverse Proxy, Web Server

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache HTTP Server Status API
Status and monitoring API for Apache HTTP Server (httpd) provided by mod_status, exposing server metrics, worker state, and load balancer information via HTTP endpoints.

**Human URL:** [https://httpd.apache.org/docs/current/mod/mod_status.html](https://httpd.apache.org/docs/current/mod/mod_status.html)

#### Tags:

 - Balancer, Metrics, Monitoring, REST, Status

#### Properties

- [Documentation](https://httpd.apache.org/docs/current/mod/mod_status.html)
- [OpenAPI](openapi/apache-httpd-status-openapi.yml)
- [JSONSchema](json-schema/httpd-serverstatus-schema.json)
- [JSON-LD](json-ld/apache-httpd-status-context.jsonld)

### Apache HTTP Server Configuration Reference
Configuration directive reference for Apache HTTP Server covering VirtualHost, mod_ssl, mod_rewrite, mod_proxy, and all core directives for web server, proxy, and SSL configuration.

**Human URL:** [https://httpd.apache.org/docs/current/mod/directives.html](https://httpd.apache.org/docs/current/mod/directives.html)

#### Tags:

 - Configuration, Reference

#### Properties

- [Documentation](https://httpd.apache.org/docs/current/mod/directives.html)

## Common Properties

- [Documentation](https://httpd.apache.org/docs/current/)
- [GettingStarted](https://httpd.apache.org/docs/current/getting-started.html)
- [GitHubOrganization](https://github.com/apache)
- [GitHubRepository](https://github.com/apache/httpd)

## Features

| Name | Description |
|------|-------------|
| mod_status Monitoring | Real-time server status endpoint providing request rates, worker states, and CPU usage. |
| mod_proxy Reverse Proxy | Full-featured reverse proxy with HTTP, HTTPS, WebSocket, and AJP protocol support. |
| mod_proxy_balancer Load Balancing | Load balancing across backend servers with byrequests, bytraffic, and bybusyness algorithms. |
| mod_ssl TLS Termination | TLS/SSL termination with client certificate authentication and OCSP stapling support. |
| mod_rewrite URL Rewriting | Powerful rule-based URL rewriting engine for redirects, proxying, and access control. |
| Virtual Hosting | Name-based and IP-based virtual hosting for serving multiple domains from a single server. |
| CGI and FastCGI | CGI and FastCGI support for dynamic content generation with external applications. |
| .htaccess Per-Directory Config | Per-directory configuration files for decentralized access control and configuration. |

## Use Cases

| Name | Description |
|------|-------------|
| Static Web Hosting | Serve HTML, CSS, JavaScript, and media files with high performance and caching headers. |
| Reverse Proxy for Applications | Proxy requests to application servers (Node.js, Python, Java) with SSL termination. |
| Load Balancing | Distribute traffic across multiple backend application instances with health checking. |
| API Gateway | Route and transform API requests using mod_rewrite and mod_proxy rules. |
| Legacy CGI Application Hosting | Run legacy CGI or PHP applications via mod_cgi, mod_fcgid, or mod_php. |

## Integrations

| Name | Description |
|------|-------------|
| mod_php | Embeds PHP interpreter directly in the Apache process for PHP application hosting. |
| Tomcat AJP Connector | AJP protocol integration with Apache Tomcat for Java web application proxying. |
| Let's Encrypt / Certbot | Automated TLS certificate provisioning with Certbot and the mod_md module. |
| Nginx | Often deployed alongside Nginx, with Nginx handling static files and Apache handling dynamic content. |
| ModSecurity WAF | ModSecurity web application firewall module for OWASP rule-based request filtering. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache HTTP Server Status API](openapi/apache-httpd-status-openapi.yml)

### JSON Schema

- 4 schema files in [json-schema/](json-schema/)

### JSON Structure

- 4 structure files in [json-structure/](json-structure/)

### JSON-LD

- [Apache HTTP Server Status Context](json-ld/apache-httpd-status-context.jsonld)

### Examples

- 4 example files in [examples/](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Apache HTTP Server Status API](capabilities/shared/httpd-status.yaml) — 4 operations for server monitoring and balancer management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Apache HTTP Server Monitoring](capabilities/httpd-server-monitoring.yaml) | httpd-status | 4 | Platform Engineer |

## Vocabulary

- [Apache HTTP Server Vocabulary](vocabulary/apache-httpd-vocabulary.yaml) — Unified taxonomy mapping 4 resources, 4 actions, 1 workflow, and 1 persona across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Apache HTTP Server Spectral Rules](rules/apache-httpd-spectral-rules.yml) — 7 rules across 4 categories enforcing Apache HTTP Server API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
