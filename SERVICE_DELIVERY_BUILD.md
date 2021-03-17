# Service Delivery: The Build Phase

Service delivery is the technical process of how a service is created. It starts
with source code created by developers and ends with a service running in
production.

## Sample Assessment Questions

- How is software built from source code to artifacts?
- Is the final artifact built from source or do developers deliver precompiled
  elements?
- What percentage of code is covered by unit tests?
- Which tests are fully automated?
- Are metrics collected about bug lead time, code lead time, and patch lead
  time?
- To build the software, do all raw source files come from version control
  repositories?
- To build the software, how many places (repositories or other sources) are
  accessed to attain all raw source files?
- Is the resulting software delivered as a single artifact, or a set of files?
- Is everything required for deployment delivered in the artifact?
- Which artifact repository is used to hand off the results to the deployment
  phase?
- Is there a single build console for status and control of all steps?
- If there is a corporate standard practice for this OR, what is it and how does
  this service comply with the practice?

## Level 1: Initial

- Each person builds in his or her own environment
- People check in code without verifying that it builds
- Developers deliver precompiled elements to be packaged
- Little or no unit testing is performed
- No metrics are collected
- Version control systems are not used to store all source files
- Building the software is a manual process or has manual steps

## Level 2: Repeatable

- The build environment is defined; everyone uses the same system for consistent
  results
- Building the software is still done manually
- Testing is done manually
- Some unit tests exist
- Source files are kept in version-controlled repositories
- Software artifacts are used as the means of delivering the end result
- If multiple platforms are supported, each is repeatable, though possibly
  independently

## Level 3: Defined

- Building the software is automated
- Triggers for automated builds are defined
- Expectations around unit test coverage are defined
- Metrics for bug lead time, code lead time, and patch lead time are defined
- Inputs and outputs of each step are defined

## Level 4: Managed

- Success/fail build ratios are measured and tracked on a dashboard
- Metrics for bug lead time, code lead time, and patch lead time are collected
  automatically
- Metrics are presented on a dashboard
- Test coverage is measured and tracked

## Level 5: Optimizing

- Metrics are used to select optimization projects
- Attempts to optimize the process involve collecting before and after metrics
- Each developer can perform the end-to-end build process in his or her own
  sandbox before committing changes to a centralized repository
- Insufficient unit test code coverage stops production
- If multiple platforms are supported, building for one is as easy as building
  for them all
- The software delivery platform is used for building infrastructure as well as
  applications
