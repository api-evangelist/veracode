# Veracode

Veracode is an application security testing (AST) platform offering static analysis (SAST), dynamic analysis (DAST), software composition analysis (SCA), manual penetration testing, and developer security training. The Veracode Platform REST APIs enable organizations to automate security testing, access findings, manage policies, generate compliance reports, and administer users and teams. All REST APIs use HMAC authentication with API ID/key credentials.

**URL:** [https://raw.githubusercontent.com/api-evangelist/veracode/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/veracode/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Application Security, SAST, DAST, SCA, Security Testing, DevSecOps

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-05-03

## APIs

### Veracode Applications REST API

Manage application profiles, sandboxes, and policy compliance. Base: `https://api.veracode.com/appsec/v1`

**Human URL:** [https://docs.veracode.com/r/c_apps_intro](https://docs.veracode.com/r/c_apps_intro)

**Tags:** Applications, Portfolio, Policy, Sandboxes

#### Properties

- [Documentation](https://docs.veracode.com/r/c_apps_intro)
- [OpenAPI](openapi/veracode-applications-openapi.yml)

### Veracode Findings REST API

Retrieve security findings from SAST, DAST, MPT, and SCA scans. Base: `https://api.veracode.com/appsec/v2`

**Human URL:** [https://docs.veracode.com/r/c_findings_v2_intro](https://docs.veracode.com/r/c_findings_v2_intro)

**Tags:** Findings, Vulnerabilities, SAST, DAST, SCA

#### Properties

- [Documentation](https://docs.veracode.com/r/c_findings_v2_intro)
- [OpenAPI](openapi/veracode-findings-openapi.yml)

### Veracode Identity REST API

Manage users, teams, business units, and API credentials. Base: `https://api.veracode.com/api/authn/v2`

**Human URL:** [https://docs.veracode.com/r/c_identity_intro](https://docs.veracode.com/r/c_identity_intro)

**Tags:** Identity, Users, Teams, Access Control

#### Properties

- [Documentation](https://docs.veracode.com/r/c_identity_intro)
- [OpenAPI](openapi/veracode-identity-openapi.yml)

### Veracode Reporting REST API

Generate asynchronous security findings and compliance reports. Base: `https://api.veracode.com/appsec/v1/analytics`

**Human URL:** [https://docs.veracode.com/r/Reporting_REST_API](https://docs.veracode.com/r/Reporting_REST_API)

**Tags:** Reporting, Analytics, Findings, Compliance

#### Properties

- [Documentation](https://docs.veracode.com/r/Reporting_REST_API)
- [OpenAPI](openapi/veracode-reporting-openapi.yml)

## Capabilities

### Shared Definitions

| File | Description |
|---|---|
| [capabilities/shared/veracode-applications.yaml](capabilities/shared/veracode-applications.yaml) | Applications API — portfolio management, sandboxes, policy compliance |
| [capabilities/shared/veracode-findings.yaml](capabilities/shared/veracode-findings.yaml) | Findings API — SAST/DAST/SCA/MPT findings retrieval |
| [capabilities/shared/veracode-identity.yaml](capabilities/shared/veracode-identity.yaml) | Identity API — users, teams, roles, credentials |
| [capabilities/shared/veracode-reporting.yaml](capabilities/shared/veracode-reporting.yaml) | Reporting API — async security reports |

### Workflow Capabilities

| Capability | APIs | MCP Tools |
|---|---|---|
| [devsecops-pipeline](capabilities/devsecops-pipeline.yaml) | Applications + Findings + Reporting | 8 tools |
| [security-administration](capabilities/security-administration.yaml) | Identity | 6 tools |

## Artifacts

| Type | Files |
|---|---|
| OpenAPI | [openapi/](openapi/) (4 specs) |
| JSON Schema | [json-schema/veracode-finding-schema.json](json-schema/veracode-finding-schema.json) |
| JSON Structure | [json-structure/veracode-finding-structure.json](json-structure/veracode-finding-structure.json) |
| JSON-LD | [json-ld/veracode-context.jsonld](json-ld/veracode-context.jsonld) |
| Examples | [examples/](examples/) (3 examples) |
| Spectral Rules | [rules/veracode-rules.yml](rules/veracode-rules.yml) |
| Vocabulary | [vocabulary/veracode-vocabulary.yml](vocabulary/veracode-vocabulary.yml) |

## Common Properties

- [Website](https://www.veracode.com/)
- [Documentation](https://docs.veracode.com/)
- [Getting Started](https://docs.veracode.com/r/REST_APIs_Quickstart)
- [Authentication - HMAC](https://docs.veracode.com/r/c_enabling_hmac)
- [GitHub Organization](https://github.com/veracode)
- [Open Source Site](https://veracode.github.io/)
- [Community](https://community.veracode.com/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
