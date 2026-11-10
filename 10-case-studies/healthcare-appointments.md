# Case Study: Healthcare Appointment Management

<small>Illustrative portfolio exercise — sample workflow, not a clinical system specification.</small>

## Problem hypothesis
Patients and hospital staff may face friction when scheduling, changing or tracking outpatient appointments.

## Actors
Patient, reception staff, clinician, appointment administrator.

## MVP workflow
1. Search for a department / clinician.
2. View eligible appointment slots.
3. Capture minimum required patient and contact details.
4. Confirm appointment and communicate status.
5. Support reschedule / cancellation under configured rules.
6. Provide staff with an auditable appointment view.

## Requirements
- Prevent conflicting bookings for the same slot.
- Apply role-based access.
- Handle unavailable slots and concurrent booking attempts.
- Support configurable appointment types and durations.
- Protect patient information and limit unnecessary data collection.
- Keep appointment status and change history traceable.

## Metrics
- Appointment completion rate.
- Slot utilisation.
- No-show rate, segmented carefully.
- Reschedule / cancellation rate.
- Average time to schedule.
- Booking-related support contacts.

## Risks and dependencies
Scheduling rules, clinician availability feeds, patient identity matching, privacy and operational training.