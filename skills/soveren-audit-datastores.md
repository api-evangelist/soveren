---
name: Audit S3, Kafka, and SQL data stores
description: Use the Soveren Object API to enumerate discovered S3 buckets, Kafka instances/topics, and SQL database instances/databases/tables for data-store posture review.
api: openapi/soveren-object-api-openapi.yml
operations: [list-s3-buckets, get-s3-bucket, list-kafka-instances, list-kafka-topics, list-sqldb-instances, list-sqldb-databases, list-sqldb-tables]
---

# Audit S3, Kafka, and SQL data stores

Authenticate with `Authorization: Bearer <token>` (Soveren app - Integrations -
External API). Base URL: `https://api.soveren.io`. All operations are read-only.

## Steps

1. **S3** — `list-s3-buckets` (`GET /api/v1/s3/buckets`, filter by `name`), then
   `get-s3-bucket` (`GET /api/v1/s3/buckets/{id}`) for a specific bucket.
2. **Kafka** — `list-kafka-instances` (`GET /api/v1/kafka/instances`), then
   `list-kafka-topics` (`GET /api/v1/kafka/topics`, filter by `instance_id`).
3. **SQL** — `list-sqldb-instances` (`GET /api/v1/sql-db/instances`), then
   `list-sqldb-databases` (`GET /api/v1/sql-db/databases`, filter by `instance_id`),
   then `list-sqldb-tables` (`GET /api/v1/sql-db/databases/{id}/tables`).

## Rules

- Page every list call with `offset`/`limit`.
- Combine with the webhook `misconfiguration` events (`policy_public_s3_bucket`,
  `policy_unencrypted_s3_bucket`, `policy_unencrypted_rds`,
  `policy_unencrypted_network`) to react to at-risk stores in real time —
  see `asyncapi/soveren-webhooks.yml`.
