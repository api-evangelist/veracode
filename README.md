# Veracode (veracode)

Veracode is an application security testing (AST) platform offering static analysis (SAST), dynamic analysis (DAST), software composition analysis (SCA), manual penetration testing, and developer security training. The Veracode Platform provides a comprehensive suite of REST APIs enabling organizations to automate security testing, access findings, manage policies, generate reports, and administer users and teams. All REST APIs use HMAC authentication with API ID/key credentials and return JSON responses following OpenAPI standards.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/veracode/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/veracode/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Application Security
- SAST
- DAST
- SCA
- Security Testing
- DevSecOps

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-05-19

## APIs

### Veracode Applications REST API

The Applications REST API provides access to all applications in a Veracode portfolio, including application profiles, policy evaluations, sandboxes, and compliance status. Enables programmatic creation, update, deletion, and querying of application profiles with filtering by name, tag, business unit, scan type, policy compliance, and modified date.

- **Human URL:** [https://docs.veracode.com/r/c_apps_intro](https://docs.veracode.com/r/c_apps_intro)
- **Base URL:** `https://api.veracode.com`

#### Tags

- Applications
- Portfolio
- Policy
- Sandboxes

#### Properties

- [Documentation](https://docs.veracode.com/r/c_apps_intro)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/veracode/refs/heads/main/openapi/veracode-applications-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/veracode-applications.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veracode-applications.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/veracode-findings.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veracode-findings.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/veracode-identity.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veracode-identity.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/veracode-reporting.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veracode-reporting.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Veracode Findings REST API

The Findings REST API retrieves security findings from static, dynamic, manual penetration testing, and SCA scans for applications. Supports filtering by CWE, severity, scan type, CVSS score, policy compliance, and annotation status. Also provides access to flaw info and MPT scan results.

- **Human URL:** [https://docs.veracode.com/r/c_findings_v2_intro](https://docs.veracode.com/r/c_findings_v2_intro)
- **Base URL:** `https://api.veracode.com`

#### Tags

- Findings
- Vulnerabilities
- SAST
- DAST
- SCA

#### Properties

- [Documentation](https://docs.veracode.com/r/c_findings_v2_intro)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/veracode/refs/heads/main/openapi/veracode-findings-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/veracode-applications.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veracode-applications.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/veracode-findings.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veracode-findings.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/veracode-identity.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veracode-identity.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/veracode-reporting.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veracode-reporting.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Veracode Identity REST API

The Identity REST API manages users, teams, business units, roles, and API credentials for a Veracode organization. Provides CRUD operations for user accounts, API service accounts, team management, and role-based access control configuration.

- **Human URL:** [https://docs.veracode.com/r/c_identity_intro](https://docs.veracode.com/r/c_identity_intro)
- **Base URL:** `https://api.veracode.com`

#### Tags

- Identity
- Users
- Teams
- Access Control

#### Properties

- [Documentation](https://docs.veracode.com/r/c_identity_intro)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/veracode/refs/heads/main/openapi/veracode-identity-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/veracode-applications.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veracode-applications.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/veracode-findings.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veracode-findings.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/veracode-identity.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veracode-identity.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/veracode-reporting.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veracode-reporting.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Veracode Reporting REST API

The Reporting REST API generates asynchronous security reports for findings, scans, deleted scans, and audit events across the Veracode portfolio. Supports filtering by application, scan type, severity, status, date range, and policy compliance.

- **Human URL:** [https://docs.veracode.com/r/Reporting_REST_API](https://docs.veracode.com/r/Reporting_REST_API)
- **Base URL:** `https://api.veracode.com`

#### Tags

- Reporting
- Analytics
- Findings
- Compliance

#### Properties

- [Documentation](https://docs.veracode.com/r/Reporting_REST_API)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/veracode/refs/heads/main/openapi/veracode-reporting-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/veracode-applications.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veracode-applications.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/veracode-findings.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veracode-findings.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/veracode-identity.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veracode-identity.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/veracode-reporting.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veracode-reporting.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/veracode)
- [Website](https://www.veracode.com/)
- [Documentation](https://docs.veracode.com/)
- [Getting Started](https://docs.veracode.com/r/REST_APIs_Quickstart)
- [Authentication](https://docs.veracode.com/r/c_enabling_hmac)
- [GitHub Organization](https://github.com/veracode)
- [Open Source Site](https://veracode.github.io/)
- [Blog](https://www.veracode.com/blog)
- [Support](https://community.veracode.com/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
