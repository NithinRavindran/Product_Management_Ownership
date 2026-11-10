# Case Study: Travel Booking Platform

<small>Illustrative portfolio exercise — hypotheses and sample scope only.</small>

## Context
A multi-service travel platform supports users searching and booking flights, hotels and related services.

## Problem hypothesis
Users may struggle to understand booking status and recover from inconsistent supplier responses across the booking journey.

## Users
- Traveller:
- Travel arranger:
- Operations / support agent:

## Discovery plan
Review booking funnel data, support contacts, supplier error categories and interviews with travellers and operations users.

## Opportunity
Improve confidence and reduce avoidable support effort by making the booking lifecycle and exception states clear.

## MVP scope
- Consistent booking status model.
- Clear pending / confirmed / failed states.
- Supplier reference and last-updated timestamp where available.
- Actionable next steps for unresolved bookings.
- Internal operational visibility for exceptions.

## Requirements
- Never show confirmed until the relevant confirmation is received and reconciled.
- Handle timeouts and unknown outcomes without duplicate booking actions.
- Provide traceability for status changes.
- Make cancellation / amendment constraints visible.

## Prioritisation
Prioritise status correctness and exception handling before cosmetic enhancements.

## Success measures
- Booking status-related support contact rate.
- Time to resolve booking exceptions.
- Confirmed booking completion rate.
- Duplicate / ambiguous booking incident rate.

## Open questions
What are the highest-volume failure modes? Which supplier statuses are reliable? What service-level commitments apply?