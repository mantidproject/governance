# Recap actions from previous meeting:

# Agenda
- Release 6.11 code freeze date. Is September 6th OK?
- Maintenance for moving to numpy v2.0 (need issue links) ([migration guide](https://numpy.org/doc/stable/numpy_2_0_migration_guide.html))
  - Need prototype(s) for how extensive the changes might be
  - Will be done on a long-running branch to integrate the changes. `main` will be auto-merged into the branch
  - numpy v2 supports python 3.9-3.12 ([python supported versions](https://devguide.python.org/versions/))
  - Need to find out status of boost::python supporting numpy v2. Related: [PR moving to boost 1.82](https://github.com/mantidproject/mantid/pull/37259)
- Mantid developer meeting and user meeting/tutorial during NOBUGS ([link](https://github.com/mantidproject/workshops/tree/main/developer/2024-09))
- Add toolz to dependencies - [link](https://anaconda.org/conda-forge/toolz)
- Review [roadmap](https://github.com/orgs/mantidproject/projects/47/views/1)
- Maintenance for mac and linux compiler versions (need issue links)
- When do we need to start building conda packages for ARM macs?
- Moving from Jenkins to GitHub Actions. Is there any reason not to do this?
- Can we move the mantid-developer environments to conda metapackages? (see [here](https://github.com/mantidproject/mantid/issues/37627) for thoughts)
- Moving to C++20 - what are the blockers? [Draft PR](https://github.com/mantidproject/mantid/pull/37838)
- AOB

Maybe revisit
- Nexus file refactoring for reflectometry
- Risk register
- [Community standards](https://github.com/mantidproject/mantid/community) according to github (Pete)
- nexus API (maintain or move?)
