## Orca Scan OpenAPI

This repository contains [OpenAPI specifications](https://www.openapis.org/) for the Orca Scan REST API.

Files can be found in the [openapi/](openapi/) directory (e.g. [spec3.yaml](openapi/spec3.yaml)).

### Why?
An OpenAPI specification makes it easier to integrate with Orca Scan's API.

### API docs
See the official guide: [Orca Scan REST API](https://orcascan.com/guides/rest-api-f09a21c3)

### Authentication

The API uses bearer token authentication.

```bash
curl -sS -H "Authorization: Bearer API_KEY" \
  https://api.orcascan.com/v1/sheets
```

### Status codes

- Global list captured in the vendor extension `x-orca-status-codes` for documentation tooling.

---

## License

[MIT License](LICENSE) © Orca Scan - a [barcode app](https://orcascan.com) with simple [barcode tracking APIs](https://orcascan.com/guides?tag=for-developers).
