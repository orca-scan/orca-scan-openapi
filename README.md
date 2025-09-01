## Orca Scan OpenAPI

This repository contains [OpenAPI specifications](https://www.openapis.org/) for OrcaScan's API.

Files can be found in the `openapi/` directory

### Why?
an OpenAPI specification makes it easier to integrate to the OrcaScan's API

### Authentication

The API uses bearer token authentication.

```bash
curl -sS -H "Authorization: Bearer API_KEY" \
  https://api.orcascan.com/v1/sheets
```

### Status codes

- Global list captured in the vendor extension `x-orca-status-codes` for documentation tooling.
