# Service Delivery: The Deployment Phase

The goal of the deployment phase is to create a running environment. The
deployment phase creates the service in one or more testing and production
environments. This environment will then be used for testing or for live
production services.

## Sample Assessment Questions

- How are artifacts deployed in production?
- How much downtime is required to deploy the service in production?
- Are metrics collected about frequency of deployment, mean time to restore
  service, and change success rate?
- How is the decision made to promote an artifact from staging to production?
- Which kind of testing is done (system, performance, load, user acceptance)?
- How is deployment handled differently for small, medium, and large releases?
- If there is a corporate standard practice for this OR, what is it and how does
  this service comply?

## Level 1: Initial

- Deployment requires manual steps
- Deployments into the staging and production environments are different
  processes, each with its own tools and procedures
- Different people on the team perform deployments differently
- Deployment requires downtime, and sometimes significant downtime
- How a release is promoted to production is ad hoc or ill-defined
- Testing is manual, ill-defined, or not done

## Level 2: Repeatable

- Deployment is performed in a documented, repeatable process
- If deployment requires downtime, it is a predictable
- Testing procedures are documented and repeatable

## Level 3: Defined

- Metrics for frequency of deployment, mean time to restore service, and change
  success rate are defined
- How downtime due to deployments is to be measured is defined; limits and
  expectations are defined
- How a release is promoted to production is defined
- Test results are clearly communicated to all stakeholders

## Level 4: Managed

- Metrics for frequency of deployment, mean time to restore service, and change
  success rate are collected automatically
- Metrics are presented on a dashboard
- Downtime due to deployments, if any, is measured automatically
- Reduced production capacity during deployment is measured
- Testing is fully automated

## Level 5: Optimizing

- Metrics are used to select optimization projects
- Attempts to optimize the process involve collecting before and after metrics
- Deployment is fully automated
- Promotion decisions are fully automated, perhaps with a few specific
  exceptions
- Deployment requires no downtime
