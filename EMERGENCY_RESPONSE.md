# Emergency Response

Emergency Response covers how outages and disasters are handled. This includes
engineering resilient systems that prevent outages plus technical and
non-technical processes performed during and after outages (response and
remediation).

## Sample Assessment Questions

- How are outages detected? (automatic monitoring? user complaints?)
- Is there a playbook for common failover scenarios and outage-related duties?
- Is there an on-call calendar?
- How is the on-call calendar created?
- Can the system withstand failures on the local level (component failure)?
- Can the system withstand failures on the geographic level (alternative
  data-centers)?
- Are staff geographically distributed (i.e., can other regions cover for each
  other for extended periods of time)?
- Do you write postmortems? Is there a deadline for when a postmortem must be
  completed?
- Is there a standard template for postmortems?
- Are postmortems reviewed to assure action items are completed?
- If there is a corporate standard practice for this OR, what is it and how does
  this service comply with the practice?

## Level 1: Initial

- Outages are reported by users rather than a monitoring system
- No one is on-call, one person is always on-call, or everyone is always on-call
- There is no on-call schedule
- There is no on-call calendar
- There is no playbook of what to do for various alerts

## Level 2: Repeatable

- A monitoring system contacts the on-call person
- There is an on-call schedule with escalation plan
- There is a repeatable process for creating the next month’s on-call calendar
- A playbook item exists for any possible alert
- A postmortem template exists
- Postmortems are written occasionally but not consistently
- On-call coverage is geographically diverse (multiple time zones)

## Level 3: Defined

- Outages are classified by severity (i.e., minor, major, critical)
- Limits (and minimums) for how often people should be on-call are defined
- Postmortems are written for all major outages
- There is an SLA defined for alert response: initial, hands-on-keyboard, issue
  resolved, postmortem complete

## Level 4: Managed

- The on-call pain is shared by the people most able to fix problems
- How often people are on-call is verified against the policy
- Postmortems are reviewed
- There is a mechanism to triage recommendations in postmortems and assure they
  are completed
- The SLA is actively measured

## Level 5: Optimizing

- Stress and/or failover testing are performed frequently (quarterly or monthly)
- “Game Day” exercises (intensive, system-wide tests) are done periodically
- The monitoring system alerts before outages occur (degraded vs. outage)
- Mechanisms exist so that any failover procedure not utilized in recent history
  is activated artificially
- Experiments are performed to improve SLA compliance
