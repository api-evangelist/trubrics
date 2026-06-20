# Trubrics (trubrics)

Trubrics is a product analytics platform for AI and LLM applications. It captures user and AI events together - prompts, generations, feedback, sign ups and conversions - through JavaScript and Python SDKs and a public HTTP ingestion API, then surfaces them as product analytics for understanding adoption, quality, and cost of AI features.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/trubrics/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/trubrics/refs/heads/main/apis.yml)

## Tags

- AI
- LLM
- Product Analytics
- Event Tracking
- Feedback

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Trubrics Event Ingestion API

Public write-only HTTP API for publishing batches of up to 100 product analytics events (user_id, event, timestamp, properties) from any client or server, authenticated with a project x-api-key.

- **Human URL:** [https://docs.trubrics.com/api_reference/](https://docs.trubrics.com/api_reference/)
- **Base URL:** `https://app.trubrics.com/api/ingestion`

#### Tags

- Events
- Tracking
- Ingestion

#### Properties

- [Documentation](https://docs.trubrics.com/new_to_trubrics/what_to_track/)
- [API Reference](https://docs.trubrics.com/api_reference/)
- [OpenAPI](openapi/trubrics-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/trubrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trubrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/trubrics)

### Trubrics LLM Event Ingestion API

Public write-only HTTP API for publishing batches of up to 100 LLM events (prompt, generation, assistant_id, latency, $thread_id) which Trubrics expands into paired prompt and generation analytics events.

- **Human URL:** [https://docs.trubrics.com/api_reference/](https://docs.trubrics.com/api_reference/)
- **Base URL:** `https://app.trubrics.com/api/ingestion`

#### Tags

- LLM
- Generations
- Ingestion

#### Properties

- [Documentation](https://docs.trubrics.com/api_reference/)
- [API Reference](https://docs.trubrics.com/api_reference/)
- [OpenAPI](openapi/trubrics-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/trubrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trubrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/trubrics)

### Trubrics Experiences and Feedback API

User feedback (thumbs, comments, conversions) is captured as standard Trubrics events through the same publish_events endpoint, letting AI experiences report sentiment and conversion signals alongside prompts and generations.

- **Human URL:** [https://docs.trubrics.com/api_reference/](https://docs.trubrics.com/api_reference/)
- **Base URL:** `https://app.trubrics.com/api/ingestion`

#### Tags

- Feedback
- Experiences
- Events

#### Properties

- [Documentation](https://docs.trubrics.com/new_to_trubrics/what_to_track/)
- [API Reference](https://docs.trubrics.com/api_reference/)
- [OpenAPI](openapi/trubrics-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/trubrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trubrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/trubrics)

## Common Properties

- [GitHub Organization](https://github.com/trubrics)
- [LinkedIn](https://www.linkedin.com/company/trubrics)
- [Website](https://www.trubrics.com)
- [Documentation](https://docs.trubrics.com)
- [Plans](plans/trubrics-plans-pricing.yml)
- [Rate Limits](rate-limits/trubrics-rate-limits.yml)
- [Fin Ops](finops/trubrics-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
