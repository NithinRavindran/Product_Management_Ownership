# Product Case Study: Corporate Travel Platform

**Domain:** Travel technology  
**Product type:** B2B corporate travel management platform

## 1. Product context

A corporate travel platform supports organisations that need employees to search, request, book and manage business travel within company policies. It also gives travel arrangers, managers and travel operations teams control over approvals, traveller information, spend visibility and post-booking servicing.

The product must balance three needs: a convenient traveller experience, policy and financial control for the organisation, and operational efficiency for the travel management team.

## 2. Users and stakeholders

| User / stakeholder | Primary need |
|---|---|
| Employee / traveller | Find suitable travel options and manage a trip |
| Travel arranger / executive assistant | Arrange travel for one or more employees |
| Line manager / approver | Review requests against policy and business context |
| Travel desk / operations agent | Handle exceptions, changes, cancellations and support |
| Corporate travel administrator | Configure policy, entities, cost centres and permissions |
| Finance / procurement | Review spend, supplier usage and reconciliation |
| Supplier / travel partner | Receive valid bookings and servicing requests |

## 3. Core product modules

### Corporate configuration
- Company entities, departments, offices and cost centres.
- Traveller profiles, preferences and travel documents where legally and operationally appropriate.
- Role-based access for travellers, arrangers, approvers and administrators.
- Configurable travel policies by employee grade, route, destination, trip type or booking category.
- Approval hierarchy, delegation and out-of-office handling.

### Search and booking
- Search flights, hotels and other supported travel services.
- Display policy indicators and explain out-of-policy options.
- Compare price, schedule, location, cancellation terms and other relevant attributes.
- Capture trip purpose, project code or cost centre where required.
- Apply negotiated corporate rates and approved supplier rules.
- Submit for approval when configured before booking.

### Approval and policy workflow
1. Traveller or arranger creates a trip request.
2. Platform evaluates selected options against configured policy.
3. In-policy requests follow the configured approval path or auto-approval rule.
4. Out-of-policy requests require reason capture and designated approval.
5. Approver reviews itinerary, policy flags and relevant cost information.
6. Approved request proceeds to booking; rejected or returned requests retain decision history.
7. Booking confirmation and itinerary are made available to the traveller and authorised stakeholders.

### Trip management and servicing
- View confirmed itinerary and booking references.
- Support cancellation, amendment and rebooking based on supplier rules.
- Communicate disruption or schedule-change information when available.
- Track service requests and operational ownership.
- Preserve a record of approvals and booking changes.

### Reporting and controls
- Spend by entity, department, cost centre and traveller segment.
- Policy compliance and out-of-policy booking reasons.
- Advance-purchase behaviour and preferred supplier usage.
- Approval turnaround time.
- Cancellation, refund and unused-ticket reporting where data is available.

## 4. Representative user journey

**Employee journey:** Sign in → enter trip details → search options → compare policy-compliant results → select itinerary → submit for approval if required → receive booking confirmation → access itinerary → request changes or cancellation.

**Approver journey:** Open pending request → review traveller, purpose, itinerary and policy status → approve, reject or request clarification → record decision and comments → track booking outcome.

**Travel operations journey:** Monitor booking state → identify supplier or ticketing exception → investigate source response → communicate next action → resolve and record the case.

## 5. Product requirements and acceptance examples

| ID | Requirement | Acceptance expectation |
|---|---|---|
| CT-01 | Apply configurable policy rules | Search results or booking requests show the applicable policy status and reason |
| CT-02 | Route approval requests | Requests reach the correct approver based on configured hierarchy and delegation |
| CT-03 | Record approval decisions | Approver, timestamp, decision and comments are auditable |
| CT-04 | Enforce role permissions | Users can only access actions and traveller data permitted by their role |
| CT-05 | Capture cost allocation | Required entity / cost centre fields are validated before booking |
| CT-06 | Manage post-booking changes | Change requests respect supplier terms and preserve the booking history |
| CT-07 | Surface booking exceptions | Pending, failed or unknown supplier outcomes are not misrepresented as confirmed |

### Example acceptance criteria

**Given** a traveller selects an option that violates a configured policy rule, **when** the request is submitted, **then** the platform captures the applicable policy exception and routes it according to the organisation's approval configuration.

**Given** an approver is unavailable and has a valid delegate configured, **when** an approval request is due, **then** the workflow follows the configured delegation rule and records the routing history.

**Given** a supplier response is uncertain after a booking request, **when** the traveller views the trip, **then** the platform displays a pending or unknown state and provides an appropriate next step rather than showing a false confirmation.

## 6. Integrations and data considerations

- Flight content and booking providers, such as GDS, NDC or airline direct connections where supported.
- Hotel aggregators, hotel chains and negotiated corporate rate sources.
- Ground transport or ancillary service providers where in scope.
- HR or identity systems for employee profile and organisational hierarchy.
- Expense, ERP or finance systems for cost allocation and reconciliation.
- Email, mobile or messaging channels for approvals and trip notifications.

Product requirements should define traveller identity matching, policy data ownership, provider response mapping, booking references, cancellation rules, payment responsibility, reconciliation and integration failure handling.

## 7. Product analytics and success measures

| Metric | What it helps evaluate |
|---|---|
| Online adoption rate | Proportion of eligible corporate bookings completed through the platform |
| Policy-compliant booking rate | Whether travellers can find and book suitable compliant options |
| Approval turnaround time | Efficiency of the approval workflow |
| Booking completion rate | Effectiveness of search-to-confirmation journey |
| Out-of-policy exception rate | Where policy or content may create friction |
| Change / cancellation handling time | Operational servicing efficiency |
| Support contact rate per trip | Clarity and reliability of the traveller journey |
| Spend visibility / allocation completeness | Quality of finance and reporting data |

Targets and baselines should be set using approved customer and product analytics data.

## 8. Roadmap example

- **Foundation:** company configuration, identity / roles, traveller profiles, policy rules and supplier connectivity.
- **Core adoption:** search, trip requests, approvals, booking status and traveller itinerary.
- **Operational maturity:** amendments, cancellations, support case management, reconciliation and reporting.
- **Optimisation:** policy insights, proactive disruption workflows and data-led travel programme improvements.

## 9. Key product risks and decisions

- Policy configuration can become difficult to maintain if rules are not transparent.
- Approval delays can create price changes and booking friction.
- Supplier booking and ticketing states need consistent mapping and reconciliation.
- Corporate traveller and travel-document data require appropriate access controls and retention.
- Policy compliance should not hide meaningful alternatives or create inaccessible workflows.
- The product must clearly distinguish a request approval from supplier booking confirmation.

## 10. Product manager focus

Align travel operations, corporate administrators, finance, approvers, travellers and engineering on policy ownership, approval paths, supplier coverage, booking and ticketing states, servicing rules, reporting definitions and the balance between traveller experience and corporate control.
