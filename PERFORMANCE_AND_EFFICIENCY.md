# Performance and Efficiency (PE)

Performance and Efficiency covers how cost-effectively resources are used and
how well the service performs. A running service needs to have good performance
without wasting resources. We can generally improve performance by using more
resources, or we may be able to improve efficiency to the detriment of
performance. Achieving both requires a large effort to bring about equilibrium.
Cost-efficiency is cost of resources divided by quantity of use. Resource
efficiency is quantity of resources divided by quantity of use. To calculate
these statistics, one must know how many resources exist; thus some kind of
inventory is required.

## Sample Assessment Questions

- What is the formula used to measure performance?
- What is the formula used to determine utilization?
- What is the formula used to determine resource efficiency?
- What is the formula used to determine cost efficiency?
- How is performance variation measured?
- Are performance, utilization, and resource efficiency monitored automatically?
  Is there a dashboard for each?
- Is there an inventory of the machines and servers used in this service?
- How is the inventory kept up-to-date?
- How would you know if something was missing from the inventory?
- If there is a corporate standard practice for this OR, what is it and how does
  this service comply with the practice?

## Level 1: Initial

- Performance and utilization are measured inconsistently
- What is measured depends on who set up the systems and services
- Resource efficiency is not measured
- Performance problems often come as a surprise and are hard to diagnose and
  resolve because there is insufficient data
- Inventory is not up-to-date
- Inventory may or may not be updated, depending on who is involved in receiving
  or disposing of items

## Level 2: Repeatable

- All metrics relevant to performance and utilization are collected across all
  systems and services
- The process for bringing up new systems and services is documented and
  everyone follows the process
- Systems are associated with services when configured for use by a service, and
  disassociated when released
- Inventory is up-to-date. The inventory process is well documented and everyone
  follows the process

## Level 3: Defined

- Performance and utilization monitoring is automatically configured for all
  systems and services during installation and removed during decommission
- Performance targets for each service are defined
- Resource usage targets for each service are defined
- Formulas for service-oriented performance and utilization metrics are defined
- Performance of each service is monitored continuously
- Resource utilization of each service is monitored continuously
- Idle capacity that is not currently used by any service is monitored
- The desired amount of headroom is defined
- The roles and responsibilities for keeping the inventory up-to-date are
  defined
- Systems for tracking devices that are connected to the network and their
  hardware configurations are in place

## Level 4: Managed

- Dashboards track performance, utilization, and resource efficiency
- Minimum, maximum, and 90th percentile headroom are tracked and compared to the
  desired headroom and are visible on a dashboard
- Goals for performance and efficiency are set and tracked
- There are periodic reviews of performance and efficiency goals and status for
  each service
- KPIs are used to set performance, utilization, and resource efficiency goals
  that drive optimal behavior
- Automated systems track the devices that are on the network and their
  configurations and compare them with the inventory system, flagging problems
  when they are found

## Level 5: Optimizing

- Bottlenecks are identified using a performance dashboard and changes are made
  as a result
- Services that use large amounts of resources are identified and changes are
  made
- Changes are reverted if the changes do not have a positive effect
- Computer hardware models are regularly evaluated to find models where
  utilization of the different resources is better balanced
- Other sources of hardware and other hardware models are regularly evaluated to
  determine if cost efficiency can improved
