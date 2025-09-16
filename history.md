# Mantid Collaboration Governance Model

Purpose of this document
========================

This document describes the revised governance framework for the Mantid Collaboration.
The governance was changed to adapt to the increasing number of partners in the project, which strained the original governance model, and to refresh the governance to reflect on-the-ground realities of how the partners are developing Mantid in response to their different needs and priorities.
The current governance is stored in the [governance file](governance.md).

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
