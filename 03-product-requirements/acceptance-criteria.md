# Acceptance Criteria

Use Given / When / Then where it improves clarity.

## Example: booking confirmation status

**Given** a user has a booking with a confirmed supplier response  
**When** the user opens booking details  
**Then** the system displays the confirmed status and confirmation reference.

**Given** the supplier has not confirmed the booking  
**When** the user opens booking details  
**Then** the system displays a pending state and a clear explanation.

## Checklist
- Happy path
- Validation and boundary conditions
- Empty and loading states
- Error and retry behaviour
- Permissions and roles
- Accessibility
- Audit trail where required
- Analytics events
- Data privacy and security
