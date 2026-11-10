# AI Agent Product Brief

## Task and user
What bounded task should the agent assist with, for whom, and why?

## Autonomy level
- Suggest only:
- Draft for approval:
- Execute with confirmation:
- Limited automatic execution:

## Tools and permissions
| Tool / action | Read or write | Permission boundary | Confirmation required |
|---|---|---|---|

## Control design
- Human approval for consequential actions.
- Allowlisted tools and destinations.
- Least-privilege access.
- Transaction limits and rate limits.
- Idempotency and audit trail.
- Stop / cancel and recovery path.

## Evaluation
Task completion, error rate, escalation rate, policy compliance, user override rate and cost.

## Threats
Prompt injection, malicious content, tool misuse, data exfiltration and unintended side effects.