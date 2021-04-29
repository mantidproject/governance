# Mantid Collaboration Governance Model

Purpose of this document
========================

This document describes the revised governance framework for the Mantid Collaboration.
The governance was changed to adapt to the increasing number of partners in the project, which strained the original governance model, and to refresh the governance to reflect on-the-ground realities of how the partners are developing Mantid in response to their different needs and priorities.

Background and Governance 2007 - 2020
=====================================

Development of Mantid started at the ISIS facility in 2007 as a project operating according to the internal ISIS process for managing capital projects.
As part of this the development team put into place specific processes for development workflow, code standards, code quality, testing and processes to on-board new developers.
In 2010 the Spallation Neutron Source (SNS) at Oak Ridge National Laboratory (ORNL) joined as a partner to make Mantid a collaborative development, which prompted the current governance structure to be introduced.

The joint development between ISIS and ORNL was built around the concept of a single project manager coordinating separate development teams, one at each facility.
The governance (which was [formalised in 2013](https://github.com/mantidproject/documents/blob/master/Project-Management/PMB/Mantid%20Governance%20Model.doc)) of the project consisted of a Project Management Board (PMB) with representatives from each facility, the project manager, a chair, and secretary.
Along with the creation of the PMB, rules of participation were introduced to formalise:

* how additional facilities joined the project;
* resource allocation based on a resource-for-use model;
* voting rights of members;
* rules for replacement of the project manager.

The role of the PMB is to monitor and discuss project progress, discuss challenges and risks and to enable effective continued collaboration.
The PMB receives reports from the project manager and chair of the technical standards committee.
Mantid release dates are agreed taking into account facility operation schedules.
The PMB also agrees dates and locations for the yearly user and developer workshops.
(Note: it is as part of its remit to enable effective continued collaboration that the PMB has initiated this process for updating the governance of the Mantid Collaboration.)

Together with the creation of the PMB, the Collaboration has held annual user and developer workshops, the first to gather scientific requirements and discuss priorities, and the other to discuss technical solutions.Requirements and technical solutions (both common and facility specific) are added to specific release cycle development periods.
Development periods are managed to culminate in a period of testing towards a fixed release date of a stable product.
The development continuously releases against a nightly-build product so that users can access new functionality as it is developed.
There are period patches as needed to the stable version of Mantid.
The development has in the past produced three or four stable releases per year, timed as far as possible to coincide with common shutdown periods at the collaborating facilities.

In the early stage of the Collaboration there was a vision that each facility would move towards similar technical solutions and workflows.
Both ISIS and SNS are pulsed spallation neutron sources with similar instrument suites and consequently similar data reduction and correction requirements.

In 2014, as the scale of the development at the two facilities grew and the code base increased, the Technical Steering Committee (TSC) was established to provide oversight for technical implementations for the development.
Membership of the TSC has been based on technical merit and experience, rather than by balance of the number of facilities in the Collaboration or resourcing level.

Additional facilities have since joined the Mantid Collaboration: the European Spallation Source (ESS) under construction in Sweden in 2015, the reactor source at the Institut Laue Langevin (ILL) in 2016, and the Chinese Spallation Neutron Source (CSNS) in 2019.
In addition, other facilities use and have contributed to Mantid but are not formally part of the Collaboration(As defined by the rules of participation set out in the original governance): the reactor sources at ANSTO (Australia), FRM-II (Germany), and the SINQ facility at the Paul Scherrer Institute (Switzerland).

Broadly speaking, the governance of Mantid has worked well. The TSC and regular annual meetings for users and developers have been effective, and the collaboration has allowed facilities to standardise on a single collaboratively developed framework for an important area of their scope.

However, the model of governance with an overall Project Management Board and single project manager has increasingly become detached from the realities of Mantid development at the collaborating facilities as their number has increased.
When the collaboration consisted of just two facilities with the same neutron production method and very similar instruments, the vision of common reduction and correction workflows was reasonable, but even then technical reasons became apparent that meant this could not always be accommodated, and often there has been disagreement between instrument scientists at the two facilities about preferred workflows.
With additional facilities now in the collaboration, both continuous sources (reactors) and pulsed sources, such differences have become more pronounced.

Whilst convergence on workflows may be a laudable aspiration, it is not essential for successful science programme delivery at the contributing facilities.
In practice, individual facilities develop their own - often very similar - reduction and correction workflows, but which are largely using common lower level algorithms which are shared with all by virtue of being contributed to the common code base.
A contributing facility’s developers work for the majority of their time on implementation for their own facility.
Where collaboration is appropriate, lower level development effort is shared between facilities.
In both instances, the TSC has been very effective in maintaining code standardisation, and in planning and coordinating large-scale core framework developments such as Mantid Workbench.
Collective maintenance periods are included in the development prior to new Mantid releases, when developers across the collaboration are involved in common housekeeping tasks.

In practice, therefore, the role of the single project manager as defined in the existing governance has become one of a development coordinator.
Each contributing facility has control over their resources, and each contributing facility has a nominated individual responsible for delivery of Mantid at that facility.
The role includes a direct interface to the broader collaboration and development.
Effective, coordinated joint development across facilities on Mantid occurs without the need of the single project manager role.

Nevertheless, the evolution to facility-centric development is not formally recognised by the PMB and single project manager model.
The consequence is that the formal governance model has largely been subverted without a definition of the roles and responsibilities in the Mantid collaboration as it now operates.

The governance of Mantid was specifically set to have a rather rigid process for facilities "officially" joining the development, the effective result of this is two tiers of use at research infrastructures.
One Tier is constituted by those "formal" members, where facilities are represented in the PMB and a second who are not.
There are three facilities who use Mantid who are not formally members of the collaboration, and are in principle not consulted on any change, major or minor.
Whilst the process for formally joining the collaboration is in principle straightforward on paper, in reality it is clearly not.

In 2020 the PMB decided to revise the governance of the project to reflect these on-the-ground realities.

The key changes are as follows.
* Removal of the single project manager role.

  * This officially recognises the importance of collaborating facilities managing and resourcing the development as required by individual facility priorities and scientific requirements.

* Rather than being run as a monolithic development, changing to a collaboration around Free/Libre Open Source Software (FLOSS) products.
  * This recognises the reality that the various facilities have their own priorities and requirements that need not align

* Introduction of a steering committee that has the remit to:
  * Hold technical and scientific roadmaps
  * Help communicate efforts from difference facilities between each other so they may align contributions
  * Provide technical management for the collaborative development

* Inclusivity for all contributing facilities and individual contributors in the development of Mantid, including sole contributors. There is no requirement that an individual contributor or facility join an organising body to participate.

Revised Governance Structure 2021 - present
===========================================

This section describes the revised governance structure for the Mantid Collaboration.
Figure 1 shows a representation of the new Steering Committee and Working Groups at the collaboration wide level, and the interactions of the Steering Committee with contributing facilities.
As such it is a stakeholder map of the development.

The box labelled "Contributing Facility Stakeholders" represents a simplified map of the stakeholders at any research facility that acts as a Contributing Facility.
These include facility scientists and Mantid developers, facility users, and key management stakeholders which would likely be executive management and budget holders.

The Mantid Collaboration governance consists of the Steering Committee which is entirely constituted by two working groups, one that develops the common scientific roadmap for the collaboration, and one that develops the common technical roadmap.

* The two working groups meet independently, but each includes representation from the other.
This ensures that the detailed work of the Scientific Roadmap Working Group is grounded by informed technical input, and the work of the Technical Roadmap Working Group is grounded in the scientific priorities and requirements of the Collaboration.
* Each Working Group shall be responsible for development and curation of a five year roadmap.
The Technical Roadmap Working Group shall be responsible for execution of both roadmaps for the immediate 12 month period.
* The Steering Committee is precisely the union of the two Working Groups.
The objective of the Steering Committee is to coordinate and manage the long term direction of Mantid, aligning it with the agreed technical and scientific priorities.
It meets as required (but at least annually) to resolve any major contention between scientific requirements and technical issues or where a significant external event impacts significantly on both the scientific and technical planning.
It also produces an annual summary for the key stakeholders.

The membership of the two Working Groups that constitute the Steering Committee comes from the contributing facilities and individual contributors.
However, the Mantid governance is agnostic to the detailed management of collaborating partners.
An example of local facility management and how it will interact with the Collaboration governance is given in the Appendix.

![steering-committee-facility](static/images/steering-committee-facility-interaction.png)

**Fig 1. Representation of the interaction between the Mantid governance and stakeholders in Contributing Facilities. The nominal limit of Steering Committee size is implemented as an initial way of working that will be adapted as necessary.**

The revised governance structure has been developed with the concept that collaboration, where appropriate, is identified and enabled, and a common code base or common code bases of open source software are developed and maintained in a collaborative way.
This model allows individual facilities to develop Mantid according to their own requirements, with accountability for delivery and resource management to their own executive management, but also levers those resources by collaboratively working with one or more other facilities where mutually beneficial.

The leading philosophy of Mantid development is that:
* The Mantid Collaboration seeks to coordinate individual contributions to a free open source software (FLOSS) project.
* Facilities (Facilities in this context refers to neutron research infrastructures such as ISIS, SNS and ILL) act as contributors to an open source software development.
This document refers to such facilities as "Contributing Facilities".
  * Mantid is open to new Contributing Facilities providing that those facilities agree to the terms listed below and can commit their own resources to develop the framework for their needs.
* Individual contributors are welcome and do not need to be part of the formal organisation or a member of a neutron scattering facility.
They are referred to in this document as “Individual Contributors”.
  * Becoming an Individual Contributor is an open process which is defined at a technical level by the workflow for contributing code.

In this model the term Contributors refers to a facility or group that contributes to the Mantid development.

**Contributing Facilities shall**
* Resource the development according to the required use by the facility (This term indicates that each Contributing Facility should have sufficient level of effort available to resource their own specific development of Mantid. As such the collaboration is a do-ocracy, in a similar way to other scientific software developments such as SASView (https://www.sasview.org/).).
* Manage local requirements and development.
* Help Mantid products remain FLOSS.
* Communicate the needs of the facility to the Steering Committee by developing and sharing the facility scientific and technical roadmaps for Mantid.
* Nominate members for the Steering Committee Working Groups who will be approved by right (Scientific Roadmap Working Group) or merit (Technical Roadmap Working Group).
* Adhere to the development workflow and standards for code quality set out by the Steering Committee.
* Contribute to maintenance and testing activities.
* Communicate with their local scientists and development team how Mantid products fit into their own larger picture for neutron and muon data analysis software.
* Be open to suggestions and feedback from Individual Contributors to the project.

**Contributing Facilities should**
* Contribute to infrastructure costs.
* Maintain a level of effort, expertise or capability in Mantid.
* Host (and fund) the annual User Meeting and Developer Workshop.

Each Contributing Facility has the responsibility to meet the Collaboration’s governance requirements and nominate membership of the Working Groups (and hence Steering Committee), as set out in sections 3.2 - 3.3. Minutes of meetings, actions and decisions will be open.

3.1 Steering Committee.
-----------------------
The Steering Committee is the body that runs the project on a consensus driven basis.
It is composed of the membership of the Scientific and Technical Roadmap Working Groups, which together steer the scientific and technical direction of the development.
The two groups communicate laterally and build consensus on the prioritisation and scheduling of common, large-scale developments.

The Working Groups that comprise the Steering Committee are described in detail in Sections 3.2 and 3.3.
The Scientific and Technical Roadmap Working Groups when meeting together as the Steering Committee have additional responsibilities as detailed below.
A primary objective is to provide a space for overall discussion between the Working Groups to encourage maximal coordination and collaboration.
The Steering Committee is tasked to hold and manage a risk register, to ensure the development is still on track, and to produce an annual summary on status and progress against the common roadmap for Contributing Facility directors and budget holders for their consideration.
The Steering Committee welcomes acknowledgement and feedback following this report.

**Membership of the Steering Committee.**

The membership of the Steering Committee is exactly the union of the Scientific and Technical Working Groups.
The primary officers of the Steering Committee are:
* A Chair, rotating on a meeting by meeting basis between the Chairs of the Scientific and Technical Roadmap Working Groups.
* A secretary elected on a permanent basis.

Contributing Facilities are expected to nominate individuals to the Scientific and Technical Working Groups, as detailed in Sections 3.2 and 3.3.
Each Contributing Facility should nominate at most two technical and two scientific experts.
Individual Contributors are welcome to join the Steering Committee in either the Scientific or the Technical Roadmap Working Group, but membership is not required in order to contribute to Mantid.
Those who contribute effort are allowed to do so in a way that benefits them, but should keep the needs and concerns of others using Mantid products in mind.

**Responsibilities of the Steering Committee.**

* Ensure coordination between Contributors.
* Ensure the Working Groups deliver publicly available scientific and technical roadmaps.
* Act as a clearing house for discussion on all matters concerning Mantid between Contributors.
* Nominate the Chairs of the User Meeting who have authority to engage a local organising committee for each User Meeting.
These individuals do not need to be members of the Steering Committee.
* Hold and maintain the development risk register.
* Collate status and progress reports as required by key stakeholders.
* Prepare an annual summary for the Contributing Facility directors.
* Hold a list of its members.
* Coordinate the review of the governance and associated documents.
* Resolve conflicts, using a defined process, where there is no consensus among collaborators.

**General Responsibilities of the Working Groups.**

* Hold a common roadmap based on their area (i.e. scientific or technical) and update it regularly.
The roadmap will reflect Contributing Facilities’ needs rather than dictate what all contributors will work on.
* Hold regular meetings with publicly circulated agendas and meeting minutes with records of decisions made.
* All members of the Steering Committee are invited to attend Working Group meetings.
* Be inclusive of Individual Contributors.
* Invite people to meetings who have a special interest in a topic or can provide greater insight than can be channeled through a Working Group member.

**General Responsibilities of members of the Working Groups.**

* Communicate the facility’s interests and intentions to the Working Groups.
* Communicate the Working Group discussions to their facility management.
* Be open to discussion of topics and work towards solutions that foster commonality through consensus.
* Attending the Working Group meetings regularly or sending a delegate where this is not possible.

| Jan            | Feb     | Mar               | Apr     | May     | Jun      | Jul     | Aug     | Sep     | Oct     | Nov     | Dec              |
| -------------- | ------- | ----------------- | ------- | ------- | -------- | ------- | ------- | ------- | ------- | ------- | ---------------- |
|                |         | Directors' Update |         |         |          |         |         |         |         |         |                  |
|                |         |                   |         |         | User Mtg |         |         |         |         |         |                  |
| Steering Cmtee |         |                   |         |         |          |         |         |         |         |         |                  |
| Tech WG        | Tech WG | Tech WG           | Tech WG | Tech WG | Tech WG  | Tech WG | Tech WG | Tech WG | Tech WG | Tech WG | Tech WG          |
|                |         | Sci WG            |         |         | Sci WG   |         |         | Sci WG  |         |         | Sci WG           |
|                |         |                   |         |         | Devel WS |         |         |         |         |         | Virtual Devel WS |

*Table 1: An example frequency of meetings for the Steering Committee, Working Groups, User Meetings and Developer Workshops. As befits its role, the Technical Roadmap Working Group meets more frequently than the Scientific Roadmap Working Group (Section 3.2). Precise dates for the User Meeting will be determined by best compromise between running periods at the Contributing Facilities to maximise attendance. [WG = Working Group; WS = workshop.]*

3.2 Periodic Review of the Mantid Governance
--------------------------------------------

The Steering Committee will be responsible for the review of the governance of the Mantid project at a suitable frequency.
This will be coordinated by the chairs of the Technical and Scientific Working Groups.
Key elements of this review process will include:
* External reviewers where appropriate.
* An evaluation of the benefits being delivered to each facility.
* An evaluation of whether the governance is facilitating or hindering collaboration.
* Updates to the governance in the spirit of continuous improvement.

3.3 Process for Resolving Conflicts
-----------------------------------

In the unlikely event where the collaboration has reached an impasse on the prioritisation or scheduling of key roadmap items, members will resort to the use of a third party conflict resolution process.
The chairs of the Scientific and Technical Working Groups will be responsible for invoking this resolution procedure.
The pair will document the issue/s and prepare an executive summary which will be sent to all participating facility directors.
The facility directors will then be invited to assume a mediation/arbitration role in a joint Steering Committee meeting which comprises the combined Scientific and Technical Working Groups.
The conflict will be presented to facility directors in detail providing each interested party to state their case.
If directors are unable to mediate a resolution, they will arbitrate the dispute and force a final decision thus providing a way out of deadlock.

3.4 Technical Roadmap Working Group and Technical Roadmap.
----------------------------------------------------------

The Technical Roadmap Working Group owns the common five year technical roadmap and coordinates effort to execute the forthcoming year’s effort on both the scientific and technical roadmaps.

**Technical Roadmap.**

The technical roadmap for the Collaboration will be composed of the common areas for technical development.
Individual facilities will build their roadmaps by embarking on a requirements gathering exercise at each facility to determine their local technical roadmap.
The wider Collaboration technical roadmap will be structured as a set of projects for which each Contributing Facility represented on the of the Working Group will assign resources (or in the case of an Individual Contributors, will undertake to contribute effort), according to the benefits-driven priority of those projects to the Contributor, in order that the project be completed.
Projects will be reviewed at each Working Group meeting so that any issues or delays can be addressed.

The roadmap will be managed as an agile project with a kanban-style representation. This will be reviewed at each of the regular meetings of the Working Group.
This visual style will facilitate effective communication of current status, complexity and interdependencies between items on the roadmap.
Topics in the roadmap will be detailed enough to foster communication, but broad enough to be relevant to multiple contributors.

Example roadmap topics include:
* File loading performance for neutron event data.
* Live streaming and infrastructure.
* Instrument geometry rendering.
* Data structure performance.
* Compatibility with external software ecosystems (e.g. pandas or PACE).
* Componentization of scientific interfaces
* Other applications such as imaging or auto-reduction which do not sit within data reduction as such.

**Membership of the Working Group.**

The base membership of the Working Group will include:
* An elected Chair.
* The Chair of the Scientific Roadmap Working Group.
* A secretary elected on a permanent basis.

Membership of the Working Group is determined by each facility.
Facilities nominate senior technical staff who are deeply involved in generating facility roadmaps at a high level, and have direct access to facility leadership.
The members of the Working Group should have a deep technical knowledge and experience over a wide range of programming, best practices, infrastructure areas and facility scientific computing roadmaps.
New members are approved by the existing Working Group.
Members must have the  authority to discuss and agree the contributions to the Collaboration roadmap.

Individual Contributors can self-nominate to be considered as members of the Working Group, or be invited by the Working Group.
The existing membership will consider and approve members on merit.

**Responsibilities of the Working Group Chair.**

The Working Group chair will be responsible for:
* Communicating the technical roadmap with Scientific Roadmap Working Group.
* Working with the Scientific and Technical Roadmap Working Groups to tension technical roadmap priorities against scientific roadmap priorities for development.
* The chair will act as “Lead Coordinator” of the overall direction and health of the project.
This ensures decisions on significant technical issues will not get stalled by the various committees.
* Resolving conflicts in the technical roadmap which cannot be resolved by consensus.
* Calling regular meetings of the Working Group.
* Attend the User Meeting

**Responsibilities of Working Group Members.**

The Working Group members will be responsible for:

* Providing and maintaining resourcing levels on agreed roadmap projects.
* Communicating progress to their local facility management.
* Translating benefits of combined projects to their local facilities.
* Communicating changes in priorities at local facilities which may affect the overall technical roadmap.

**Terms of Reference.**

The Technical Roadmap Working Group is responsible for the following activities and processes:
* Partners the Scientific Roadmap Working Group as equal members within the Steering Committee.
* Senior managers who have significant control or influence over data reduction resource within their respective facilities.
* Creates and delivers a technical roadmap for the Collaboration.
* Communicates the technical roadmap to the Scientific Roadmap Working Group and changes as they take place.
* Working Group members should encourage experts in key areas to attend where appropriate.
* Provides technical grounding for items in the scientific roadmap created and owned by the Scientific Roadmap Working Group.
* To come up with the best technical solutions for a given major and submitted problems.
* Promotes consensus on infrastructure and processes.
* Coordinates and advises on major designs.
* Coordinates changes to the third party dependencies of Mantid and makes recommendations for changes and updates.
* Ensures there is a good distribution of developers with administrator privileges for services.
* Acts as an arbitration and triage point for conflicts.
* Overseeing, resourcing and scheduling large-scale refactoring effort.

The Technical Roadmap Working Group operates on the following basis:
* The Working Group will meet at least monthly online.
* The Working Group will meet face-to-face at least annually as a satellite to the User Meeting.
* All members of the Steering Committee are invited to attend meetings.
* People can be invited to meetings who have a special interest or insight in a topic that cannot be channeled through a Working Group Member.
* The technical roadmap is reviewed at every meeting as the first agenda item.
* The Working Group organises the annual face-to-face Developer Workshop and the virtual Developer Workshop.
* Membership is determined by Contributing Facility recommendations or (self-)nomination of Individual Contributors.
New membership is approved by the existing membership.
* The Working Group will elect a Chair from within the existing membership.
* The position of Chair is for a fixed term appointment, reviewed annually by the Working Group.
* Holds a list of its membership.
* The agenda and minutes of Working Group meetings will be published publicly.
* The Working Group can be contacted by anyone outside the Collaboration via a mailing list.

3.5 Scientific Roadmap Working Group and Scientific Roadmap.
------------------------------------------------------------

The Scientific Roadmap Working Group owns the common five year scientific roadmap.
This group will meet every three months to review and update as necessary the scientific roadmap in accordance with the common development plan and Contributing Facilities’ evolving scientific roadmaps.

**Scientific Roadmap.**

The scientific roadmap for the Collaboration will be composed of common areas for scientific development.
Each individual facility will be responsible for creating its own scientific roadmap alongside its own technical roadmap through processes that it sees as fit for its own local management of Mantid.
The scientific roadmaps from all Contributing Facilities will be shared in the Scientific Roadmap Working Group, along with input from Individual Contributors and the User Meeting.
Common requirements will be identified and initiated as projects between those Contributing Facilities that assign resources, and Individual Contributors who undertake to contribute effort, that will enable the projects to be completed.
Projects will be reviewed at each Working Group meeting as part of the constant review and updating of the common scientific roadmap.
The management of common projects on the 12 month view is the responsibility of the Technical Roadmap Working Group, which will review common projects at each meeting so that any issues or delays can be addressed.

The Steering Committee and Scientific Roadmap Working Group own a common - not a global- scientific roadmap.
It is not the intention that they own the totality of the roadmap of all facilities, or to attempt prioritisation of scientific requirements for any single Contributing Facility.
The common roadmap is developed to enable collaboration on areas of common interest.
The Scientific Roadmap Working Group has access to the roadmaps of all the Contributing Facilities in order to identify and promote collaborative projects.

**Membership of the Working Group.**

The base membership of the Working Group will include:
* An elected Chair.
* The Chair of the Technical Roadmap Working Group
* At least one person, but a maximum of two, per Contributing Facility.
* A secretary elected on a permanent basis.

The Chair is elected from the current membership of the Working Group.
Additional representatives from the Technical Roadmap Working Group can be co-opted as required to provide specialist technical input.
The meeting is open for any members of the Technical Roadmap Working Group to participate in if they choose.

Membership  will primarily (It is expected that most members will be facility staff.
The Scientific Roadmap Working Group is open to membership from non-facility staff.
Individuals should communicate their willingness to join the Working Group by contacting the Chair of the Working Group) be via nominated staff from facilities.
It is expected that nominated staff will have a good understanding of the development and of their facility roadmap.
Members must have the authority to discuss and agree the contributions to the common Collaboration roadmap.

**Responsibilities of the Working Group Chair.**

The Working Group chair will be responsible for:
* Presenting the scientific roadmap to the Technical Roadmap Working Group.
* Working with the Technical and Scientific Roadmap Working Groups to tension technical roadmap priorities against scientific roadmap priorities for development.
* Raising issues with the Technical Roadmap Working Group and share with members of the Scientific Roadmap Working Group.
* Informing the User Meeting of the scientific roadmap and acting as an interface between the User Meeting and Scientific Roadmap Working Group.
* Calling extraordinary meetings of the Scientific Roadmap Working Group as needed.
* Attending the User Meeting.

**Responsibilities of Working Group Members.**

The Working Group members will be responsible for:
* Presenting Contributing Facilities roadmaps to the Scientific Roadmap Working Group
* Communicating changes in the local facilities roadmaps to the Scientific Roadmap Working Group
* Communicating the scientific roadmap to their local facility management and Mantid governance

**Terms of Reference.**

The Scientific Roadmap Working Group is responsible for the following activities and  processes:
* Create and deliver the scientific roadmap for the Collaboration.
* Communicate the common scientific roadmap to the Technical Roadmap Working Group.
* Communicate the Contributing Facility scientific roadmaps to the Technical Roadmap Working Group.
* Promote and foster collaboration between contributors by finding commonalities which could involve two or more Contributing Facilities which could then evolve into projects in the common scientific roadmap.
* Work with the Technical Roadmap Working Group to ensure that the scientific priorities are satisfied with technically feasible solutions.

The Scientific Roadmap Working Group operates on the following basis:
* The Working Group will meet at least quarterly online.
* The Working Group will meet face-to-face at least annually as a satellite to the User Meeting.
* All members of the Steering Committee are invited to attend meetings.
* People can be invited to meetings who have a special interest or insight in a topic that cannot be channeled through a Working Group Member.
* The scientific roadmap will be reviewed every meeting as the first item on the agenda.
* Membership is determined by Contributing Facility nomination.
* The Working Group will elect a Chair from within the existing membership.
* The position of Chair is a fixed term appointment, reviewed annually by the Working Group.
* Holds a list of its membership.
* The agenda and minutes of Working Group meetings will be published publicly.
* The Working Group can be contacted by anyone outside the Collaboration via a mailing list.

**Features of the Mantid Scientific Roadmap.**

* The roadmap will be a high level scientific outlook on a technique-by-technique basis.
  * Inputs will be based on milestones and deliverables for each technique area as included in each of the Contributing Facilities shared roadmaps.
  * The output will be a distillation of the shared roadmap needs from a discussion within the steering group
  * The roadmap shall highlight common aspects.
  * The roadmap will provide horizon scanning, including new instruments and techniques.
  * Contributors are encouraged to share scientific outlooks that are not necessarily  envisioned to be developed within Mantid. (Specific exclusions from the Mantid roadmap are useful. A collective view on scientific computing across the Contributing Facilities helps to identify and define the scope of the overall project.)
* The formation of the roadmap will be an iterative process. At one meeting of the Scientific Roadmap Working Group areas for collaboration on projects will be identified from the Contributing Facility roadmaps; outside the Working Group these will be formulated by the interested Contributors into projects, and incorporated into the Mantid development in a subsequent meeting.
* The technique areas to be considered could include:
  * Powder diffraction
  * Single crystal diffraction
  * Macromolecular crystallography
  * Engineering diffraction
  * Disordered materials
  * Small angle neutron scattering (SANS)
  * Reflectometry
  * Imaging & computed tomography
  * Spectroscopy
    * Direct geometry
    * Indirect geometry
    * Triple axis spectrometer
    * Neutron spin echo
    * Deep inelastic
    * Quasi-elastic neutron scattering (QENS)
    * Muon spin rotation

3.6 User Meeting and Developer Workshop
---------------------------------------

These meetings will be organised with the aim of enabling an effective  connection between contributors and users of Mantid and the applications produced using the Mantid framework.
There will be two meetings held back-to-back: the first centered on scientific usage and needs (User Meeting), and the other centered on technical discussions (Developer Workshop).

**User Meeting**

The Collaboration shall organise an annual face-to-face user meeting. The Steering Committee will facilitate this by:
* Electing a Chair for the meeting.
* Agreeing on a host and date for the meeting.
* Ensuring there is a point of contact in each Working Group who is willing to help identify key themes for the meeting.
* Providing a list of contacts for Individual Contributors with whom local contributions to the meeting can be discussed.

The elected chair will organise the meeting with the aim of:
* Informing users on the latest news and ‘hot’ topics relating to the Mantid collaboration.
* Promoting interaction between contributors to stay abreast of new advances in techniques for data reduction/analysis across different scientific areas.
* Promoting interaction between developers and scientists to improve understanding of scientific requirements and technical constraints.
* Identifying common areas of development between contributors, and promoting collaborative work both through immediate discussion and in feedback to the Steering Committee.
* Discussing new technologies/infrastructures which may be leveraged to enhance the user experience.
* Addressing both technical and scientific topics, and providing constructive feedback to the Steering Committee as to whether the respective roadmaps are meeting user needs.

The elected chair will make a report to the Steering Committee following the User Meeting.

**Developer Workshop**

This annual face-to-face meeting is organised by the Technical Roadmap Working Group and is organised alongside the User Meeting.
There may also be additional virtual Developer Workshops throughout the year.
The Technical Roadmap Working Group is responsible for creating an agenda for the meeting.

The purpose of the Developer Workshop is as follows:
* Promote interaction between developers, from both Contributing Facilities and Individual Contributors.
* Run code camps to work on backlog issues (defined by the Technical Roadmap Working Group) or issues that benefit from a more interactive approach to problem solving.
* Discuss new technologies and infrastructures which may be leveraged to enhance the project.
* Gather feedback on day-to-day working practices and identify points for improvement.



Appendix: Example for interaction from a Contributing Facility
==============================================================

The diagram below provides ISIS-specific detail on the interaction with the wider collaboration governance.
This represents a concrete example  of how a facility might interact with the collaboration-wide governance.
ISIS intends to have an internal Mantid Programme Board which comprises scientists and technical leads who determine the ISIS-specific roadmap for Mantid.
They will have sufficient authority within the facility to make decisions regarding the direction of Mantid-based data reduction and analysis software development on behalf of ISIS.
This body will decide which projects constitute the Mantid programme of work, in line with the local scientific and technical roadmap that the body creates and owns.
The board will report to internal management structures so they can have a view of whether the project is continuing to deliver for the facility.
The project-based approach, if adopted by other facilities, will allow for a better understanding of areas of overlap and the timing of such developments.
Technical leads will schedule the resources within the development team to deliver against this roadmap.

![isis-internal-governance](static/images/isis-internal-governance-example.png)

Key features of the ISIS approach are:
* The Mantid Programme may consist of projects which are completely external or shared development with other facilities.
* These projects will arise from the internal scientific/technical roadmaps.
Roadmaps will be developed as the result of a series of deep-dive requirements gathering workshops within each science group.
* The technical requirements which satisfy the scientific roadmap will be extracted as part of this exercise.
Purely technical requirements will be consumed from the development team.
* The local scientific roadmap will be developed by the Data Reduction Strategist (this is one aspect of the person responsible for the overall ISIS Scientific Computing strategy) and the Scientific Roadmap Working Group Representative.
They have the delegated authority to decide on projects which satisfy the data reduction computing requirements for the facility.
* The local technical roadmap will be developed by the Data Reduction Lead and the Data Reduction Budget holder in line with the scientific computing strategy for the facility.
The technical roadmap will deliver the requirements stemming from the scientific roadmap as well as any purely technical requirements which are prerequisites for the fulfilment of the scientific requirements.
* Each ISIS representative on the Scientific andTechnical Roadmap Working Groups will communicate the local ISIS roadmap to those Working Groups.
Collaborative projects will be created out of areas of common interest, however, they will also maintain a distinct internal representation.


The diagram below shows the local ILL implementation with respect to the steering committee (Mantid Collaboration):

![ill-internal-governance](static/images/ill-internal-governance-example.png)
