# API Integration Brief

## Business purpose
[What user or business outcome does this integration enable?]

## Systems and ownership
- Calling system:
- Provider system:
- Business / technical owners:

## Contract overview
| Item | Detail |
|---|---|
| Base URL / environment | Securely managed configuration |
| Authentication | OAuth2 / API key / other; never store secrets here |
| Methods and endpoints | [Document approved endpoints] |
| Request / response schema | Link to OpenAPI contract |
| Rate limits | [Provider agreement] |
| Timeout / retry policy | [Engineering decision] |

## Product behaviours
- Success:
- Validation failure:
- Provider unavailable:
- Timeout / unknown outcome:
- Duplicate request:
- Reconciliation:

## Non-functional requirements
Latency, availability, security, auditability, privacy and observability.

## Acceptance and monitoring
Define contract tests, key metrics, alert thresholds and operational ownership with engineering.