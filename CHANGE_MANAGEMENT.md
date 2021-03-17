# Change Management

Change Management covers how services are deliberately changed over time. This
includes the software delivery platform—the steps involved in a software
release: develop, build, test, and push into production. For hardware, this
includes firmware upgrades and minor hardware revisions.

## Sample Assessment Questions

- How frequently are production deployments performed?
- How much human labor does it take?
- When a release is received, does anything need to be changed before it is pushed?
- How does operations know if a release is major or minor, a big or small
  change? How are these types of releases handled differently?
- How does operations know if a release is successful?
- How often have releases failed?
- Are there change-freeze windows?
- If there is a corporate standard practice for this? If so, what is it and how does
  this service comply with the practice?

## Level 1: Initial

- Deployments are done sparingly, as they are very risky
- The deployment process is ad hoc and laborious
- Developers notify operations of new releases when a release is ready for
  deployment
- Releases are not deployed until weeks or months after they are available
- Operations and developers bicker over when to deploy releases

## Level 2: Repeatable

- The deployment is no longer ad hoc
- Deployment is a manual but consistent process
- Releases are deployed as delivered
- Deployments fail frequently

## Level 3: Defined

- What constitutes a successful deployment is defined
- Minor and major releases are handled differently
- The expected time gap between release availability and deployment is defined

## Level 4: Managed

- Deployment success/failure is measured against definitions
- Deployments fail rarely
- The expected time gap between release availability and deployment is measured

## Level 5: Optimizing

- Continuous deployment/delivery utilized
- Failed deployments are extremely rare
- New releases are deployed with little delay
