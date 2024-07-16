Attendees: Sarah, Remi, Oleksandr, Pete

# Recap actions from previous meeting:

# Agenda
- Draft of [release milestones](https://github.com/mantidproject/mantid/milestones) for next year
  - plan for end of January and end of May
- Maintenance for moving to numpy v2.0 (need issue links) ([migration guide](https://numpy.org/doc/stable/numpy_2_0_migration_guide.html))
  - Would like to incrementally move from 1.24 to 1.25 then 1.26
  - Need prototype(s) for how extensive the changes might be
  - Will be done on a long-running branch to integrate the changes. `main` will be auto-merged into the branch
  - What is the minimum python version?
  - Need to find out status of boost::python supporting numpy v2. Related: [PR moving to boost 1.82](https://github.com/mantidproject/mantid/pull/37259)
- Mantid developer meeting and user meeting/tutorial during NOBUGS ([link](https://github.com/mantidproject/workshops/tree/main/developer/2024-09))
  - Pete will copy more details into the tutorial agenda
  - Pete will create NOBUGS2024 slack channel
  - Pete will share meeting folder with participants
- Deprecation policy - see draft [link](https://github.com/mantidproject/workshops/blob/main/developer/2023-10/codecamp/deprecation_policy.md)
  - minor edits on the policy then it will go into place in the user documentation
- Add toolz to dependencies - [link](https://anaconda.org/conda-forge/toolz)
  - ISIS will coordinate with euphonics who is requesting this change
- Review [roadmap](https://github.com/orgs/mantidproject/projects/47/views/1)
- AOB

August's meeting
- Maintenance for mac and linux compiler versions (need issue links)
- When do we need to start building conda packages for ARM macs?
- Moving from Jenkins to GitHub Actions. Is there any reason not to do this?
- Can we move the mantid-developer environments to conda metapackages? (see [here](https://github.com/mantidproject/mantid/issues/37627) for thoughts)
  
Maybe revisit
- Nexus file refactoring for reflectometry
- Risk register
- [Community standards](https://github.com/mantidproject/mantid/community) according to github (Pete)
- nexus API (maintain or move?)
