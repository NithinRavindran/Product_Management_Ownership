# Product Metrics Catalogue Across Four Product Domains

This catalogue links common product measurement concepts to the four product environments in this portfolio. Metrics are candidates, not claims of actual performance.

## Common product metrics

| Metric | Definition | Useful segmentation | Caveat |
|---|---|---|---|
| Activation rate | Eligible new users completing a defined activation event | Channel, cohort, role | Define activation and eligibility |
| Conversion rate | Users progressing from one defined funnel stage to another | Channel, device, segment | Maintain consistent denominators |
| Feature adoption | Eligible active users using a feature in a period | Feature, cohort, role | Distinguish trial from repeat use |
| Retention | Cohort users returning / completing a value event in a later period | Signup cohort, segment | Define return event and window |
| Time to value | Time from defined start to first realised value event | Segment, channel | Handle outliers and incomplete data |
| Reliability | Successful transactions divided by eligible attempts | Integration, service, version | Classify expected failures |

## Domain-specific candidate metrics

### Corporate Travel Management

| Metric | Product question |
|---|---|
| Request completion rate | Can employees complete travel requests? |
| Approval turnaround | How efficiently are requests reviewed? |
| Policy compliance rate | Are eligible bookings within configured policy? |
| Booking success rate | Are approved trips successfully confirmed by suppliers? |
| Traveller satisfaction | Is the end-to-end trip experience meeting expectations? |
| Forecast accuracy | How closely do travel spend forecasts match actual spend? |
| Mobile trip engagement | Are travellers using mobile capabilities for meaningful trip tasks? |

### B2B & B2C Travel Technology

| Metric | Product question |
|---|---|
| Search-to-book conversion | Do users find relevant products and complete bookings? |
| Checkout abandonment | At which step do users leave the purchase journey? |
| Supplier success rate | Which supplier connections reliably return bookable inventory? |
| Price-change rate | How often do offers materially change before booking? |
| Package completion rate | Are all required package components confirmed? |
| Agency activation / repeat booking | Are B2B partners adopting and returning to the platform? |
| Customer retention | Do B2C customers return for future travel needs? |

### Healthcare System — HIMS / EHR / Laboratory

| Metric | Product question |
|---|---|
| Workflow completion rate | Are users completing the intended administrative / clinical workflow? |
| Order-to-result turnaround | How long does the defined laboratory process take? |
| Interface processing success | Are device / system messages processed correctly? |
| Unmatched result rate | How often can results not be safely matched to an order / specimen? |
| Duplicate message / result rate | Are retransmissions handled without duplicate records? |
| Interface exception backlog | Are integration issues visible and resolved? |
| System availability | Are critical workflows available when needed? |

### Vulnerability & Incident Management

| Metric | Product question |
|---|---|
| Scan coverage | Are in-scope assets being assessed? |
| Finding freshness | How current are vulnerability findings? |
| Time to triage | How quickly are findings and alerts reviewed? |
| Mean time to acknowledge / remediate | How effectively are incidents and vulnerabilities handled? |
| Actionable alert conversion | Are security signals creating useful response work? |
| SLA compliance | Are agreed response and remediation targets met? |
| Reopen rate | Are closed incidents and remediation outcomes holding? |

## Metric governance

For every KPI, record:
- Business definition and product question.
- Formula, numerator and denominator.
- Eligibility and exclusions.
- Data source and event definition.
- Segmentation and reporting period.
- Owner and review cadence.
- Data quality and known limitations.

Do not compare metrics across domains without accounting for different workflows, risk profiles, user populations and definitions. Never publish confidential or unverified production metrics.
