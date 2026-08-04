# Veracode (veracode)

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
