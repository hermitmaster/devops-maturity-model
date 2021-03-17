# Capacity Planning

Capacity planning covers determining future resource needs. All services require
some kind of planning for future resources. Services tend to grow. Capacity
planning involves the technical work of understanding how many resources are
needed per unit of growth, plus non-technical aspects such as budgeting,
forecasting, and supply chain management.

## Sample Assessment Questions

- How much capacity do you currently have?
- How much capacity do you expect to need three months from now? Twelve months
  from now?
- What statistical models, if any, are used for determining future needs?
- How do you load-test?
- How much time does capacity planning take? What could be done to make it
  easier?
- Are metrics collected automatically?
- Are metrics always available or is a manual process initiated to collect them?
- Is capacity planning the job of no one (everyone), a person (role), or a team?
- If there is a corporate standard practice for this? If so, what is it and how
  does this service comply with the practice?

## Level 1: Initial

- No inventory is kept
- The system runs out of capacity from time to time
- Determining how much capacity to add is done by tradition, guessing, or luck
- Fulfillment of additional capacity is reactive, often not being able to
  fulfill the demand for capacity in time
- Capacity planning has no owner
- Current resources are underutilized (over-sized)

## Level 2: Repeatable

- Capacity planning metrics are collected on demand, or as needed
- The process for collecting capacity planning metrics is written and repeatable
- Load testing is done occasionally, perhaps when a service is new
- Inventory of all resources is accurate, possibly due to manual effort

## Level 3: Defined

- Capacity planning metrics are automatically collected
- Capacity required for a certain amount of growth is well-defined
- There is a dedicated capacity planning person on the team
- Capacity planning requirements are defined at a subsystem Level
- Load testing is triggered by major software and hardware changes
- Inventory is updated as part of capacity changes
- The amount of headroom needed to survive typical surges is defined

## Level 4: Managed

- Capacity planning metrics are collected continuously
- Additional capacity is gained automatically, with human approval
- Performance regressions are detected during testing, involving CP if
  performance regression will survive into production (i.e., it is not a bug)
- Dashboards include capacity planning information.
- Changes in correlation are automatically detected and raise a ticket for
  Capacity planning to verify and adjust relationships between core drivers and
  resource units
- Unexpected increases in demand are automatically detected using metrics or
  similar technique, which generates a ticket for the capacity planning person
  or team.
- The amount of headroom in the system is monitored

## Level 5: Optimizing

- Past capacity planning projections are compared with actual results
- Load testing is done as part of a continuous test environment
- The team employs a data scientist
- Additional capacity is gained automatically
- The amount of headroom is systematically optimized to reduce waste
