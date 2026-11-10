# Technical Product Management

This section captures the technical understanding needed to define products and collaborate effectively with engineering. It shows how technical product thinking applies across the four product domains; it is not a substitute for engineering design or specialist clinical / security review.

## Contents
- [API integration brief](api-integration-brief.md)
- [System context template](system-context-template.md)
- [Integration failure handling](integration-failure-handling.md)
- [Technical requirements checklist](technical-requirements-checklist.md)

## Technical product considerations by domain

| Product domain | Technical product topics |
|---|---|
| Corporate Travel | HR / identity integration, flight and hotel supplier APIs, policy data, booking state orchestration, notification and finance integrations |
| B2B & B2C Travel Tech | GDS / NDC / airline connectivity, hotel / activity / transfer supply, pricing and inventory, channel separation, payment and dynamic package orchestration |
| Healthcare Systems | HIMS / EHR / LIS interoperability, patient and specimen identity, HL7 / ASTM or vendor-specific device interfaces, result validation, auditability and privacy |
| Vulnerability & Incident Management | Scanner integration, asset / CMDB context, SIEM correlation, event normalisation, incident state machines, SLA tracking and security controls |

## What a Product Manager should understand

- System boundaries and key actors.
- APIs, request / response contracts and data ownership.
- Integration dependencies and failure scenarios.
- Authentication, permissions and data protection.
- Asynchronous workflows, retries, idempotency and reconciliation.
- Performance, reliability, scalability and observability.
- Technical trade-offs and their effect on user and business outcomes.

## Collaboration principle

The Product Manager owns problem clarity, product outcomes, requirements and prioritisation. Engineering owns detailed technical design and implementation decisions. Work together early on feasibility, dependencies, risks and options.
