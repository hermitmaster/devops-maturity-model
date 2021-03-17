# Monitoring and Metrics (MM)

Monitoring and Metrics covers collecting and using data to make decisions.
Monitoring collects data about a system. Metrics uses that data to measure a
quantifiable component of performance. This includes technical metrics such as
bandwidth, speed, or latency; derived metrics such as ratios, sums, averages,
and percentiles; and business goals such as the efficient use of resources or
compliance with a service level agreement (SLA).

## Sample Assessment Questions

- Is the service level objective (SLO) documented? How do you know your SLO
  matches customer needs?
- Do you have a dashboard? Is it in technical or business terms?
- How accurate are the collected data and the predictions? How do you know?
- How efficient is the service? Are machines over- or under-utilized? How is
  utilization measured?
- How is latency measured?
- How is availability measured?
- How do you know if the monitoring system itself is down?
- How do you know if the data used to calculate key performance indicators
  (KPIs) is fresh? Is there a dashboard that shows measurement freshness and
  accuracy?
- If there is a corporate standard practice for this OR, what is it and how does
  this service comply with the practice?

## Level 1: Initial

- No SLOs are documented
- If there is monitoring, not everything is monitored, and/or it is impossible
  verify completeness
- Systems and services are manually added to the monitoring system, if at all
- There are no dashboards
- Little or no measurement or metrics
- You think customers are happy, but they are not
- It is common (and rewarded) to enact optimizations that benefit a person or
  small group to the detriment of the larger organization or system
- Departmental goals emphasize departmental performance to the detriment of
  organizational performance

## Level 2: Repeatable

- The process for creating machines/server instances assures they will be
  monitored

## Level 3: Defined

- SLOs are documented
- Business KPIs are defined
- The freshness of business KPI data is defined
- A system exists to verify that all services are monitored
- The monitoring system itself is monitored (meta-monitoring)

## Level 4: Managed

- SLOs are documented and monitored
- Defined KPIs are measured
- Dashboards exist showing each step’s completion time; the lag time of each
  step is identified
- Dashboards exist showing current bottlenecks, backlogs, and idle steps
- Dashboards show defect and rework counts
- Capacity planning is performed for the monitoring system and all analysis
  systems
- The freshness of the data used to calculate KPIs is measured

## Level 5: Optimizing

- The accuracy of collected data is verified through active testing
- KPIs are calculated using data that is less than one minute old
- Dashboards and other analysis displays are based on fresh data
- Dashboards and other displays load quickly
- Capacity planning for storage, CPU, and network of the monitoring system is
  done with the same sophistication as any major service
