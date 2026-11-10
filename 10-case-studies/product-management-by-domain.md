# Product Management Responsibilities Across Four Product Domains

This matrix connects common Product Manager responsibilities to the specific product context of each portfolio area.

## Product strategy and outcomes

| PM responsibility | Corporate Travel | B2B & B2C Travel Tech | Healthcare System | Vulnerability & Incident Management |
|---|---|---|---|---|
| Product vision | Simplify and control corporate travel | Enable reliable multi-product travel commerce | Connect hospital and clinical workflows | Turn security signals into managed risk-reduction work |
| User value | Easier trip planning, policy clarity and traveller support | Relevant choice, transparent pricing and dependable booking | Accurate, timely and connected patient / lab information | Clear prioritisation, ownership and remediation status |
| Business outcomes | Adoption, compliant spend and operational efficiency | Conversion, partner growth, booking success and commercial performance | Workflow efficiency, interoperability and data integrity | Faster triage, reduced exposure and SLA performance |
| Strategic trade-offs | Traveller convenience vs policy control | Supplier breadth vs speed, reliability and margin | Workflow speed vs clinical safety and validation | Automation vs explainability and false-positive risk |

## Discovery and stakeholder management

| PM activity | Corporate Travel | B2B & B2C Travel Tech | Healthcare System | Vulnerability & Incident Management |
|---|---|---|---|---|
| Primary users | Traveller, arranger, approver, travel manager | Traveller, agent, agency admin, operations | Patient, clinician, lab technician, hospital admin | Security analyst, incident responder, asset owner |
| Discovery focus | Request friction, approval delays, policy exceptions | Search behaviour, conversion barriers, supplier issues | Patient / encounter workflow, lab turnaround, interface exceptions | Alert noise, risk prioritisation, incident hand-offs |
| Stakeholder alignment | HR, finance, procurement, travel operations | Suppliers, commercial, finance, customer support | Clinical, lab, hospital operations, IT | Security, infrastructure, SOC, engineering |

## Requirements and product execution

| PM activity | Corporate Travel | B2B & B2C Travel Tech | Healthcare System | Vulnerability & Incident Management |
|---|---|---|---|---|
| Core requirements | Policy engine, approvals, trip / booking states | Catalogue, search, pricing, package and booking states | HIMS / EHR / LIS data flows, result validation | Scanner ingestion, correlation, incident lifecycle |
| Critical edge cases | Supplier timeout, multi-city date / time, partial trip confirmation | Price change, duplicate booking, partial package failure | Patient / specimen mismatch, duplicate result, device outage | Duplicate finding, false positive, alert correlation error |
| Technical collaboration | HRIS, GDS / airlines, hotel suppliers, expense systems | GDS / NDC, airline / hotel / activity / transfer APIs, payment | HL7 / ASTM or vendor interface, LIS, analyser middleware | Scanner APIs, SIEM, CMDB / asset inventory |
| UAT focus | Policy, approval, booking and servicing scenarios | Channel, product, supplier and package scenarios | Patient identity, order / result and device scenarios | Finding lifecycle, correlation, SLA and remediation scenarios |

## Product analytics and success measures

| Product domain | Example outcome metrics |
|---|---|
| Corporate Travel | Request completion, approval turnaround, policy compliance, booking success, traveller satisfaction, spend forecast accuracy |
| B2B & B2C Travel Tech | Search-to-book conversion, checkout completion, supplier success, price-change rate, package completion, agency activation, repeat booking |
| Healthcare System | Order-to-result turnaround, interface processing success, unmatched result rate, duplicate message rate, workflow completion and availability |
| Vulnerability & Incident Management | Scan coverage, finding freshness, time to triage, MTTA / MTTR, actionable alert conversion, SLA compliance, reopen rate |

These are candidate metrics. Each requires an agreed definition, denominator, source, time window, owner and data-quality check before use.

## Common PM artefacts applied across the four domains

- Product vision and strategic outcomes.
- User research plan, personas and journey maps.
- Problem statements and opportunity assessments.
- PRD, functional and non-functional requirements.
- User stories and acceptance criteria.
- Prioritisation framework and decision log.
- Product roadmap, dependency map and release plan.
- UAT scenarios and release readiness checklist.
- KPI catalogue, event tracking and product dashboards.
- Risk register and post-launch review.

## Product Manager operating rhythm

| Cadence | Typical PM activities |
|---|---|
| Continuous | User / stakeholder conversations, requirement clarification, product decisions |
| Weekly | Backlog refinement, delivery dependency review, KPI and issue review |
| Per sprint | Planning, scope alignment, acceptance clarification and demo feedback |
| Per release | UAT readiness, go / no-go input, release communication and monitoring |
| Monthly / quarterly | Outcome review, roadmap refresh, strategic trade-offs and stakeholder alignment |

The operating rhythm should be adapted to product maturity, team structure, regulatory context and delivery model.
