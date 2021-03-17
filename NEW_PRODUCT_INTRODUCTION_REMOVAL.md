# New Product Introduction and Removal (NPI/NPR)

New Product Introduction and Removal covers how new products and services are
introduced into the environment and how they are removed. This is a coordination
function: introducing a new product or service requires a support infrastructure
that may touch multiple teams.

For example, before a new model of computer hardware is introduced into the
datacenter environment, certain teams must have access to sample hardware for
testing and qualification, the purchasing department must have a process to
purchase the machines, and datacenter technicians need documentation. For
introducing software and services, there should be tasks such as requirements
gathering, evaluation and procurement, licensing, and creation of playbooks for
the helpdesk and operations.

Product removal might involve finding all machines with an old release of an
operating system and seeing that all of them get upgraded. Product removal
requires identifying current users, agreeing on timelines for migrating them
away, updating documentation, and eventually decommissioning the product, any
associated licenses, maintenance contracts, monitoring, and playbooks. The
majority of the work consists of communication and coordination between teams.

## Sample Assessment Questions

- How is new hardware introduced into the environment? Which teams are involved
  and how do they communicate? How long does the process take?
- How is old hardware or software eliminated from the system?
- What is the process for disposing of old hardware?
- Which steps are taken to ensure disks and other storage are erased when
  disposed?
- How is a new service or new software brought into being? Which teams are
  involved and how do they communicate? How long does the process take?
- What is the process for hand-off between teams?
- Which tools are used?
- Is documentation current?
- Which steps involve human interaction? How could it be eliminated?
- If there is a corporate standard practice for this OR, what is it and how does
  this service comply with the practice?

## Level 1: Initial

- New products are introduced through ad hoc measures and individual heroics
- Teams are surprised by NPI, often learning they must deploy something into
  production with little notice
- NPI is delayed due to lack of capacity, miscommunication, or errors
- Deprecating old products is rarely done, resulting in operations having to
  support an “infinite” number of hardware or software versions

## Level 2: Repeatable

- The process used for NPI/NPR is repeatable
- The handoff between teams is written and agreed upon
- Each team has a playbook for tasks related to its involvement with NPR/NPI
- Equipment erasure and disposal is documented and verified

## Level 3: Defined

- Expectations for how long NPI/NPR will take are defined
- The handoff between teams is encoded in a machine-readable format
- Members of all teams understand their role as it fits into the overall process
- The maximum number of products supported by each team is defined
- The list of each team’s currently supported products is available to all teams

## Level 4: Managed

- There are dashboards for observing NPI and NPR progress
- The handoff between teams is actively revised and improved
- The number of no-longer-supported products is tracked
- Decommissioning no-longer-supported products is a high priority

## Level 5: Optimizing

- NPI/NPR tasks have become API calls between teams
- NPI/NPR processes are self-service by the team responsible
- The handoff between teams is a linear flow (or for very complex systems,
  joining multiple linear flows)
