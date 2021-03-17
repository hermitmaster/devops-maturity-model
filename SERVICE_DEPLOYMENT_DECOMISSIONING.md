# Service Deployment and Decommissioning

Service Deployment and Decommissioning covers how instances of an existing
service are created and how they are turned off (decommissioned). After a
service is designed, it is usually deployed repeatedly. Deployment may involve
turning up satellite replicas in new datacenters or creating a development
environment of an existing service. Decommissioning could be part of turning
down a datacenter, reducing excess capacity, or turning down a particular
service instance such as a demo environment.

## Sample Assessment Questions

- What is the process for turning up a service instance?
- What is the process for turning down a service instance?
- How is new capacity added? How is unused capacity turned down?
- Which steps involve human interaction? How could it be eliminated?
- How many teams touch these processes?
- Do all teams know how they fit into the over all picture?
- What is the workflow from team to team?
- Which tools are used?
- Is documentation current?
- If there is a corporate standard practice for this OR, what is it and how does
  this service comply with the practice?

## Level 1: Initial

- The process is undocumented and haphazard. Results are inconsistent
- The process is defined by who does something, not what is done
- Requests get delayed due to miscommunication, lack of resources, or other
  avoidable reasons
- Different people perform tasks differently

## Level 2: Repeatable

- The processes required to deploy or decommission a service are understood and
  documented
- The process for each step is documented and verified
- Each step has a QA checklist to be completed before handing off to the next
  step
- Teams learn of process changes by other teams ahead of time.- Information or
  processing needed by multiple steps is created once
- There is no (or minimal) duplication of effort
- The ability to turn up new capacity is a repeatable process
- Equipment erasure and disposal is documented and verified

## Level 3: Defined

- The SLA for how long each step should take is defined
- For physical deployments, standards for removal of waste material (boxes,
  wrappers, containers) are based on local environmental standards
- For physical decommissions, standards for disposing of old hardware are based
  on local environmental standards as well as the organization’s own standards
  for data erasure
- Tools exist to implement many of the steps and processes

## Level 4: Managed

- The defined SLA for each step is measured
- There are feedback mechanisms for all steps
- There is periodic review of defects and reworks
- Capacity needs are predicted ahead of need
- Equipment disposal compliance is measured against organization standards as
  well as local environmental law
- Waste material (boxes, wrappers, containers) involved in deployment is
  measured
- Quantity of equipment disposal is measured

## Level 5: Optimizing

- After process changes are made, before/after data is compared to determine
  success
- Process changes are reverted if before/after data shows no improvement
- Process changes that have been acted on come from a variety of sources
- Cycle time enjoys month-over-month improvements
- Decisions are supported by modeling “what if” scenarios using extracts from
  actual data
- Equipment disposal is optimized by the reduction of equipment deployment
