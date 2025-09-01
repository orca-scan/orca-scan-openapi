## Orca Scan OpenAPI

This repository contains [OpenAPI specifications](https://www.openapis.org/) for OrcaScan's API.

Files can be found in the `openapi/` directory

### Why?

- Single source of truth for endpoints, models, and auth
- Generate SDKs/clients in many languages from one spec
- Power interactive docs (Swagger UI/Redoc) without duplicating content
- Enable validation, contract testing, and breaking-change detection in CI
- Reduce onboarding time for integrators and internal teams

### Authentication

The API uses bearer token authentication.

```bash
curl -sS -H "Authorization: Bearer API_KEY" \
  https://api.orcascan.com/v1/sheets
```

### Status codes

- Global list captured in the vendor extension `x-orca-status-codes` for documentation tooling.
