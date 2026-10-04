---
name: veracode-reports-generate-and-fetch
description: Generate an analytics report and then retrieve its results.
api: openapi/veracode-reports-api-openapi.yml
operations:
- generateReport
- getReport
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/veracode-reports-api-openapi.yml ; every operationId checked against the contract
---

# veracode-reports-generate-and-fetch

Generate an analytics report and then retrieve its results.

## Steps

1. 1. Call `generateReport` with the required request body as defined in the API contract.
2. 2. Call `getReport` with the `reportId` path parameter returned from `generateReport`.

## Rules

- Authentication: Include an `Authorization` header using the HmacAuth scheme (http).
- Pagination: Use query parameters `page` and `size` where applicable.
