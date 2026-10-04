---
name: veracode-manage-team
description: Create, retrieve, update, delete, and list teams in Veracode.
api: openapi/veracode-teams-api-openapi.yml
operations:
- createTeam
- getTeam
- updateTeam
- deleteTeam
- listTeams
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/veracode-teams-api-openapi.yml ; every operationId checked against the contract
---

# veracode-manage-team

Create, retrieve, update, delete, and list teams in Veracode.

## Steps

1. 1. Use `createTeam` with a JSON body containing the team details and include the HmacAuth header.
2. 2. Use `getTeam` with the path parameter `teamId` and include the HmacAuth header.
3. 3. Use `updateTeam` with the path parameter `teamId`, a JSON body of updated fields, and include the HmacAuth header.
4. 4. Use `deleteTeam` with the path parameter `teamId` and include the HmacAuth header.
5. 5. Use `listTeams` with optional query parameters `page` and `size` for pagination and include the HmacAuth header.

## Rules

- Auth: All requests require the HmacAuth HTTP authentication header.
- Pagination: `listTeams` supports `page` and `size` query parameters.
- Errors: On rate‑limit exhaustion the API returns no specific HTTP status code (None).
