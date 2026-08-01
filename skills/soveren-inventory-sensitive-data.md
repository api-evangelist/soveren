---
name: Inventory sensitive data across the environment
description: Use the Soveren Object API to enumerate detected data types, the assets that handle them, and the data flows between assets.
api: openapi/soveren-object-api-openapi.yml
operations: [get-data-types, get-clusters, get-assets, get-asset, get-asset-data-flows]
---

# Inventory sensitive data across the environment

Soveren's Object API is read-only. Authenticate every request with a bearer token
generated in the Soveren app under **Integrations - External API**:
`Authorization: Bearer <token>`. Base URL: `https://api.soveren.io`.

## Steps

1. **List detected data types** — `get-data-types` (`GET /api/v1/data-types`) to see
   which sensitive data types Soveren has discovered.
2. **List clusters** — `get-clusters` (`GET /api/v1/clusters`) to get the Kubernetes
   clusters under observation.
3. **List assets** — `get-assets` (`GET /api/v1/assets`), optionally filtered by
   `cluster_id` and `namespace`. Page with `limit` and `offset`.
4. **Inspect an asset** — `get-asset` (`GET /api/v1/assets/{id}`) for details.
5. **Trace data flows** — `get-asset-data-flows` (`GET /api/v1/assets/{id}/data-flows`)
   to see which data types move to/from the asset. Page with `limit`/`offset`.

## Rules

- Read-only: all operations are `GET`; there is no idempotency-key contract.
- Paginate with `offset`/`limit` on every list call.
- On `401` re-check the bearer token; on `404` verify the object id by listing the
  parent collection first.
