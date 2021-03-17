# Disaster Preparedness

A DevOps organization needs to be able to handle outages well, and it must have
practices in-place that minimize the chance of repeating previous failures.
Disasters and major outages happen. Everyone in the company from the top down
needs to recognize that fact, and adopt a mind-set that accepts outages and
learns from them. Systems should be designed to be resilient to failure.

## Sample Assessment Questions

- What is the SLA? Which tools and processes are in place to ensure that the SLA
  is met?
- How complete are the playbooks?
- When was each scenario in the playbooks last exercised?
- What is the mechanism for exercising different failure modes?
- How are new team members trained to be prepared to handle disasters?
- Which roles and responsibilities apply during a disaster?
- How do you prepare for disasters?
- How are disasters used to improve future operations and disaster response?
- If there is a corporate standard practice for this OR, what is it and how does
  this service comply with the practice?

## Level 1: Initial

- Disasters are handled in an ad hoc manner, requiring individual heroics
- Playbooks do not exist, or do not cover all scenarios
- Little or no training exists
- Service resiliency and different failure scenarios are never tested

## Level 2: Repeatable

- Playbooks exist for all failure modes, including large-scale disasters
- New team members receive on-the-job training
- Disasters are handled consistently, regardless of who is responding
- If multiple team members respond, their roles and responsibilities are not
  clearly defined, leading to some duplication of effort

## Level 3: Defined

- The SLA is defined, including dates for postmortem reports
- Hand-off procedures are defined, including checks to be performed and
  documented
- How to scale the responding team to make efficient use of more team members is
  defined
- The roles and responsibilities of team members in a disaster are defined
- Disaster preparedness training for new team members is defined and implemented
- The team has regular disaster preparedness exercises
- The exercises include fire drills performed on the live service
- After every disaster, a postmortem report is produced and circulated

## Level 4: Managed

- The SLA is tracked using dashboards
- The timing for every step in the process from the moment the event occurred is
  tracked on the dashboard
- A program for disaster preparedness training ensures that all aspects are
  covered
- The disaster preparedness program measures the results of disaster
  preparedness training
- As teams improves at disaster response, training expands to cover more complex
  scenarios
- Teams are involved in cross-functional fire drills that involve multiple teams
  and services
- Dates for publishing initial and final postmortem reports are tracked and
  measured against the SLA

## Level 5: Optimizing

- Areas for improvement are identified from the dashboards
- New techniques and processes are tested; the results are measured and used in
  further decision-making
- Automated systems ensure that every failure mode is exercised within a certain
  period, by artificially causing a failure if one has not occurred naturally
