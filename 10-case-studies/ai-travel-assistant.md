# Case Study: AI-powered Travel Assistant

<small>Illustrative portfolio exercise — not a claim of a launched AI product.</small>

## Problem hypothesis
Travellers may need help comparing options, understanding policies and navigating post-booking questions across fragmented information.

## Target users
Travellers who need contextual assistance during search, booking and post-booking journeys.

## Product vision
Provide a helpful travel assistant that answers grounded questions and guides users through approved workflows while keeping consequential actions under user control.

## MVP
- Answer FAQs using approved travel content.
- Explain policy and booking information with source references.
- Collect missing context through structured questions.
- Route unsupported or sensitive cases to human support.
- Do not purchase, cancel or amend a booking without explicit confirmation and authorised workflow controls.

## AI design
- Retrieval from approved, access-controlled content.
- Clear citations and freshness indicators.
- No-answer behaviour when evidence is insufficient.
- Prompt-injection and data-leakage safeguards.
- Evaluation set covering normal, ambiguous and adversarial queries.

## Metrics
- Resolved-without-escalation rate (with quality guardrail).
- Answer groundedness and citation correctness.
- Task completion rate.
- Escalation and recontact rate.
- Latency and cost per successful task.

## Risks
Outdated supplier content, hallucinated policy guidance, privacy exposure and user overreliance.

## Validation plan
Start with offline evaluation and a human-reviewed pilot before expanding scope.