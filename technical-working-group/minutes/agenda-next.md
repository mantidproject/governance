Attendees: Peterson, Perenon, Hampson

# Recap actions from previous meeting:

# Agenda
- mantid v6.10 smoke tests are scheduled for Thursday
- Maintenance is happening on main to move forward compiler versions for mac and linux
- numpy v2.0.0 was recently released with breaking changes to the c-api. We are waiting until boost-python supports it
- When do we need to start building conda packages for ARM macs?
  - Checking usage reports to see if users are moved already
  - Will need to support eventually
  - Probably not move until there are more builders. Dependencies are already ready
- Mantid developer meeting and user meeting/tutorial during NOBUGS ([link](https://github.com/mantidproject/workshops/tree/main/developer/2024-09))
  - Follow up with TWG in two weeks to find out who is attending from mantid community to find volunteers to lead
- Review [roadmap](https://github.com/mantidproject/roadmap/projects/1)
  - [Mantid error reporter improvements](https://github.com/mantidproject/roadmap/issues/32) is approaching ready. Notable feature is automatically creating github issues from reports if it is not a duplicate
  - [Replacing fitting engine study](https://github.com/mantidproject/roadmap/issues/20) has much of the information it needs, but is incomplete
  - [LoadEventNexus for non-filtering workflows](https://github.com/mantidproject/roadmap/issues/36) is largely complete and may get a small PR later
- AOB

Maybe revisit
- Nexus file refactoring for reflectometry
- Risk register
- [Community standards](https://github.com/mantidproject/mantid/community) according to github (Pete)
- nexus API (maintain or move?)
