# Integration Failure Handling

| Failure mode | User-facing behaviour | System behaviour to agree with engineering | Monitoring |
|---|---|---|---|
| Timeout | Clear pending / unknown status; avoid false confirmation | Safe retry and reconciliation policy | Timeout rate |
| Rate limit | Explain temporary delay where relevant | Backoff and quota management | 429 rate |
| Validation error | Actionable correction message | Reject invalid request with traceable error | Validation failures |
| Provider outage | Status transparency and support path | Circuit breaking / queueing where appropriate | Availability |
| Duplicate callback | No duplicate user transaction | Idempotent processing | Duplicate event count |

Do not automatically retry non-idempotent operations without an agreed idempotency and reconciliation strategy.