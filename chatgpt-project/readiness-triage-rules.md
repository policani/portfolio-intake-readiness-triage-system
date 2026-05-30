# Readiness Triage Rules

Score each dimension from 0 to 3.

| Score | Meaning |
|---:|---|
| 0 | Absent or materially unclear |
| 1 | Weak, assumed, or incomplete |
| 2 | Usable but needs confirmation |
| 3 | Clear enough for routing |

## Dimensions

1. Sponsorship
2. Problem clarity
3. Evidence
4. Urgency or decision need
5. Dependency and capacity visibility
6. Routing fit

## Total score guidance

| Score | Default interpretation |
|---:|---|
| 0-5 | Reject or hold unless there is a mandatory external driver |
| 6-9 | Clarify; enough signal to investigate but not enough to route cleanly |
| 10-13 | Route candidate with specific gaps and assumptions |
| 14-18 | Ready for a downstream route if sponsor and decision rights are clear |

## Override rules

- No confirmed sponsor: do not classify as ready for business case, charter, or scoring. Use clarify or hold unless a sponsor-confirmation step is the immediate route.
- Clear regulatory, audit, legal, or security driver: do not reject solely because evidence is incomplete. Route to urgent clarification or executive triage.
- Solution without problem: classify as clarify unless a real problem can be stated from provided evidence.
- Duplicate request: reject or hold unless new evidence changes the decision.
- Capacity-blind mandate: do not mark as execution-ready; flag capacity decision required.
