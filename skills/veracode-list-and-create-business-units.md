---
name: veracode-list-and-create-business-units
description: Retrieve a paginated list of business units and then create a new business unit.
api: openapi/veracode-business-units-api-openapi.yml
operations:
- listBusinessUnits
- createBusinessUnit
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/veracode-business-units-api-openapi.yml ; every operationId checked against the contract
---

# veracode-list-and-create-business-units

Retrieve a paginated list of business units and then create a new business unit.

## Steps

1. 1. Use `listBusinessUnits` with query parameters `page` and `size` to fetch business units.
2. 2. Use `createBusinessUnit` with the required request body (fields not specified in the documentation) to add a new business unit.

## Rules

- Auth: Include an HmacAuth header as defined by the provider.
- Pagination: Use `page` and `size` query parameters for `listBusinessUnits`.
- Errors: No specific error codes documented.
