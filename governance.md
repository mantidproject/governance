# Mantid Collaboration Governance Model

Purpose of this document
========================

This document describes the governance model for the Mantid Collaboration.
The history of the governance is stored in the [history file](history.md).

Table of Contents
=================

- [Mantid Collaboration Governance Model](#mantid-collaboration-governance-model)
- [Purpose of this document](#purpose-of-this-document)
- [Table of Contents](#table-of-contents)
- [Governance Model](#governance-model)
  - [General to all Working Groups](#general-to-all-working-groups)
  - [Process for Resolving Conflicts](#process-for-resolving-conflicts)
  - [Technical Working Group (TWG) and the Committed Collaborative Roadmap (CCR)](#technical-working-group-twg-and-the-committed-collaborative-roadmap-ccr)
  - [3.5 User Communication Working Group (UCWG).](#35-user-communication-working-group-ucwg)
  - [3.2? Governance Model Reviews and the GMWG](#32-governance-model-reviews-and-the-gmwg)
  - [3.? Developer Workshop](#3-developer-workshop)
  - [User Meeting](#user-meeting)
  - [Coffee with Scientists and Users](#coffee-with-scientists-and-users)
- [Appendix: Example for interaction from a Contributing Facility](#appendix-example-for-interaction-from-a-contributing-facility)


Governance Model
================

The governance structure is developed to stimulate collaboration and resulting in open source code that is developed and maintained in a collaborative way.

Key to Mantid development, and two types of contributors:

* The Mantid Collaboration seeks to coordinate contributions to a free open source software (FLOSS) project.
* Facilities (Facilities in this context refers to research infrastructures such as ISIS, SNS and ILL) act as contributors to an open source software development.
This document refers to such facilities as "Contributing Facilities".
  * Mantid is open to new Contributing Facilities providing that those facilities conform to the terms listed in this document and can commit their own resources to develop the framework for their needs.
* Individual contributors are welcome and do not need to be a member of a facility.
They are referred to in this document as “Individual Contributors”.
  * Becoming an Individual Contributor is an open process as defined in this document. Contributions are not limitted to code commits, and refer to any contributions that help the purpose of the collaboration.

![steering-committee-facility](static/images/overview-governance-model-2026.png)

**Fig 1. Representation of the interaction between the collaborative part (top box) and Contributing Facilities (bottom box). The components next to the top box are described further below. The two components that are shaded out are optional to the collaborative governance model.**

Figure 1 shows a representation of how the cross facility part of the governance interact with each Contributing Facility.
The box labelled "Cross Facility Governance Working Groups (WGs)" shows the collaborations bodies, in the form of three Working Groups (WPs), which makes up the collaborative bodies of the governance model. 
The box labelled "Each Contributing Facility" shows a simplified map of the stakeholders of a Contributing Facility.
These include facility scientists, developers, users, and a "board" of some kind that oversees and prioritises Mantid needs for a single facility. The latter will vary from facility to facility, e.g. from a single developer and a couple of scientists meeting informally to discuss prioritises to a larger board with several science representatives helping to prioritise Mantid requirements across 20+ instruments for a larger facility development team.
It is not prescribed how such a "board" is run or setup, but it is assumed that contain communication happens between the Contributing facility and the cross facility WGs, as described in this document.

This governance model allows individual facilities to develop Mantid according to their own requirements, with accountability for delivery and resource management to their own executive management, while leverage collaboratively working where this is of mutually beneficial.

In short the Collaborative WGs in figure 1 are:

* The Technical Working Group (TWG) - maintain and update a Committed Roadmap and responsible for running Mantid Developer Workshops
* The User Communication Working Group (UCWG) - cover user communication not covered by other means and the facilitation of [User Meetings](#user-meeting) and optionally Coffee thing 
* Optional: The Governance Model Working Group (GMWG) - its purpose is to periodically review and update this document and governance model, including to check that it is not become out-of-date. This is meant to a WG in the lighted sense possible, periodically (e.g. yearly) review and update this governance model, with option to feed in ideas ongoingly.

Examples of local facility management is given in the Appendix.

**Contributing Facilities shall**
* Resource the development according to the required use by the facility (i.e. each Contributing Facility will have sufficient level of effort available to resource their own specific development of Mantid. As such the collaboration is a do-ocracy, in a similar way to other scientific software developments such as SASView (https://www.sasview.org/).).
* Provide own local management, requirement gathering process and development.
* Nominate members to WGs.
* Help Mantid products remain FLOSS.
* Adhere to the development workflow and standards for code quality set out by the Technical Working Group (TWG).
* Contribute to maintenance and testing activities.
* Be open to contributions, suggestions and feedback from Individual Contributors.

**Contributing Facilities should**
* Contribute to infrastructure costs.
* Maintain a level of effort, expertise or capability in Mantid.
* Host (and fund) User Meetings and Developer Workshops.


General to all Working Groups
------------------------------

All Working Groups (WGs) runs on a consensus driven basis and share several common aspects of working whick is described in this section.

A primary aim of all WGs is to provide spaces for discussions between facilities to encourage coordination and collaboration.

**Membership.**

Each Contributing Facility can nominate at most two members per WG. New WP members are approved by the existing WP members.
A Contributing Facility is a facility that has dedicated developer resource (part time or full time) working on Mantid or is paying another Contributing Facility money to maintain and develop Mantid.
All meetings are open to guests in the form of Individual Contributors, people who have a special interest and knowledge of a topic, and facilities interested in experiencing the working of a WG before requesting membership or as part of considering becoming a Contributing Facility. 
Guests cannot cast votes where votes are held in WG meetings. Guest can self-nominate to attend WG meetings (for whom to contact see the WG membership lists) or be invited by a WG member (where this is not the chair please inform the chair ahead of the meeting the guest attend).
With regards to Individual Contributors, note being a member of a facility is not required in order to contribute to Mantid. Anyone who contribute, facility member or Individual Contributor, are allowed to do so in a way that benefits them, but should keep the needs and concerns of others using Mantid products in mind.

**The base membership of a WG.**

The base membership of the WG will include:
* An elected Chair.
* An elected Secretary. The secretary can be a non voting member, in this regard, in the same way as a guest.

**Responsibilities of the WG Secretary.**

* Calls regular meetings of the WG with agendas (if this is not done by the chair).
* Writes meeting minutes with records of decisions made and brief high-level summary of discussions. Minutes shall be comprehensible by the primary relevant audience of the WG, for instance for the TWG other Mantid developers.

**General Responsibilities of all members of the WGs.**

* Communicate the facility’s interests and intentions to the WGs.
* Communicate WG discussions and outcomes to their facility management.
* Be open to discussion of topics and work towards solutions that foster commonality through consensus.
* Be open to receive request from self-nominated guests and be open to invite guests to join WG meetings.
* Attend the WG meetings regularly or send a delegate where this is not possible.

**General Responsibilities of each WG.**

* Hold a up to date publicly accessible list of its members, and optionally Individual Contributors.
* Hold recurrent meetings with publicly circulated agendas and meeting minutes with records of decisions made.
* Will elect a Chair from within the existing membership. The position of Chair is for a fixed term appointment, reviewed annually by the WG.
* Will elect a Secretary that can be a person external to the WG. The position of Secretary is for a fixed term appointment, reviewed annually by the WG.
* The WG can be contacted by anyone outside the Collaboration via a mailing list (where such exists, see individual WG, or by reaching out to the chair or other WG members on the membership lists.

Below is an example of how the frequency of WG meetings could be (as of Nov 2025, this is how these are run for the TWG).

| Jan  | Feb  | Mar  | Apr  | May  | Jun  | Jul  | Aug  | Sep  | Oct  | Nov  | Dec  |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| GMWP |      |      |      |      |      |      |      |      |      |      |      |
| TWG  | TWG  | TWG  | TWG  | TWG  | TWG  | TWG  | TWG  | TWG  | TWG  | TWG  | TWG  |
|      |      | UCWG |      |      | UCWG |      |      | UCWG |      |      | UCWG |

*Table 1: An example frequency of meetings for the collaborative WGs. The cadence of User Meetings and Developer Workshops are determined by the UCWG and TWG respectively.*


Process for Resolving Conflicts
-------------------------------

In the unlikely event where the collaboration has reached an impasse, members will resort to the use of a third party conflict resolution process.
The chairs of the Technical and User Communication WGs will be responsible for invoking this resolution procedure.
The pair will document the issue/s and prepare a summary which will be sent to all participating facility directors.
The facility directors will then be invited to assume a mediation/arbitration role in a joint meeting which comprises the combined Technical and User Communication WGs.
The conflict will be presented to facility directors in detail providing each interested party to state their case.
If directors are unable to mediate a resolution, they will arbitrate the dispute and force a final decision thus providing a way out of deadlock.
The need for using this conflict resolution process should be rare, and since its introduction in 2021 it has not been used.


Technical Working Group (TWG) and the Committed Collaborative Roadmap (CCR)
---------------------------------------------------------------------------

The Technical Working Group (TWG) owns the Comitted Collaborative Roadmap (CCR) and the Developer Workshops (for the collaboration).
It coordinates technical discussions with an emphasis on those that concerns multiple faciliities.

**Committed Collaborative Roadmap (CCR).**

In short, this roadmap will contain large work items that are needed to keep Mantid operational and deployable on the OS platforms that facilities requires it to run on, and any new user capabilities that one or more Contributing Facilities have committed resources for and the TWG have been informed about.

In more detail, the CCR is composed of broadly the following two catagories of work items/topics: 

* (large) work items needed to keep Mantid operating and being fit for the the future. For example, existtential work to keep up to date with 3rd party dependencies such as Python and Qt, keep the development pipeline functional, keep Mantid deployable on relevant platforms, keep a tap on technical debt, handle future instrument data rate and read/write rates, security etc. 
The CCR work items for which one or more Contributing Facilities have committed resources for (or in the case of an Individual Contributors, will undertake the work). In addition, discussions between TWG members may identify new existential Mantid needs that in return TWG members will communicate back to their facility management. When resource from one or more facilities has been committed to a work item it can be associated with a future release on the CCR.
* (large) work items to enhance Mantid with new capabilities such as to handle of new instruments and instrument upgrades, improving the scientific accuracy of data reduction for a specific technique, support of new type data reduction, user usability needs etc. as needed by individual facilities.
Work items of this kind only appear on the CCR once at least one facility has committed resources to it. 
By making such work visible on the CCR the whole collaboration can see what is upcoming, which may stimulate further interest and potential additional contributions.
Scientific technique areas include: Powder diffraction, Single crystal diffraction, Engineering diffraction, Disordered materials, Small angle neutron scattering (SANS), Reflectometry, and Spectroscopy (Direct geometry, Indirect geometry, Triple axis spectrometer, Neutron spin echo, Deep inelastic, Quasi-elastic neutron scattering (QENS), Muon spin rotation).

There will naturally also be topics that might be argued to fit into both of the above two catagories such as: specific needs to help support external live streaming infrastructure, cross-cutting instrument geometry changes, deprecation or support for compatibility with 3rd party software interfaces etc..

![steering-committee-facility](static/images/TWG-CCR-requirement-funnels-2026.png)

**Fig 2. Shows the connection between the TWG and to its right a partial snapshot of the CCR (see here for full and up to date version), and below these the connection between the TWG and requirement funnels / gathering processes controlled by individual Contributing Facilities.**

The CCR is managed using Agile with a kanban-style representation. It is reviewed at each of the regular meetings of the Working Group.
As can be seen here (link direct to CCR or roadmap repo) its visual style is aimed at facilitating effective communication of past, current and future work items against releases.
Topics in the roadmap are detailed enough to foster communication, while broad enough to be relevant to multiple contributors.

For information applicable to all WGs see [here](#general-to-all-working-groups).

**Membership specific to the TWG.**

Nominated members should be senior technical staff who are involved in local core Mantid work and/or local facility Mantid team leads and/or have oversight over local facility Mantid roadmap needs.
Members must have the authority to discuss and agree the contributions to the collaboration roadmap.

This WG operates a mailing list which is twg@mantidproject.org.

**Responsibilities specific to all TWG Members.**

* Provide and maintain resource levels on agreed roadmap items.
* Attend and facilitate Developer Workshops.
* Encouraged to attend User Meetings.

**Responsibilities of the TWG Chair.**

* Ensure the CCR gets discussed and updated at each TWG meeting.
* The chair will act as “Lead Coordinator” of the overall direction and health of the CCR.
This ensures decisions on significant technical issues will not get stalled.
* Resolving conflicts in the roadmap which cannot be resolved by consensus.
* Calling regular meetings of the WG (the Secretary might do this instead).
* Attend User Meetings

**Responsibilities specific to the TWG.**

* (should this responsibility be included?) Holds and maintains a development risk register, which is only solely with keeping track of known risks that may risk Mantid can't be deployed on relevant facility OS platforms or developer no longer can sufficiently easily contribute to Mantid (e.g. due to obsolesent devops component) or other similar existential risk to Mantid.
* Maintains and updates the Committed Collaborative Roadmap (CCR).
* Communicates relevant items on the CCR will local facility management and vice versa.
* Provides technical feedback on items brought forward to the TWG.
* Promotes consensus on infrastructure and processes.
* Coordinates and advises on major designs.
* Coordinates changes to the third party dependencies of Mantid and makes recommendations for changes and updates.
* Ensures there is a good distribution of developers with administrator privileges for services.
* Acts as an arbitration and triage point for conflicts.
* Overseeing, resourcing and scheduling large-scale refactoring effort.

**Operations specific to the TWG**

* The WG will meet at least monthly online.
* The WG will meet face-to-face at least annually.
* The WG organises the annual face-to-face Developer Workshop and (optionally) virtual Developer Workshops.
* (repeat?) The CCR is reviewed at every meeting.


3.5 User Communication Working Group (UCWG).
------------------------------------------------------------

This WG purpose is to:

* Keep neutron and muon community informed about the present state of Mantid - including to debunk myths that were once true but no longer are true.
* Sharing information from the Committed Collaboration Roadmap (CCR) in ways that can benefit from reaching a larger audience.
* WG that is open to receive feedback from users not covered by other means, such as on stories that they can help with desiminate to a wider audience.
* Capture users experience that might be easier to collect at a collaboration level rather thatn by an individual facility, and advise on how a local facility can conduct their own user surveys.
* Facilitate the [User Meetings](#user-meeting).
* Facilitate Coffee with Scientists and Users. 

For information applicaable to all WGs see [here](#general-to-all-working-groups).

**Membership info specific to the UCWG.**

Made up of members who are interested in user communication both for collaboration for within individual facilities.

Nominated members can be: 
* Scientists with understanding of local Mantid user needs 
* Developers with understanding of local Mantid needs
* Facility staff with experience in communication and faciliting user meetings
*  intestaff who are involved in local core Mantid work and/or local facility Mantid team leads and/or have

Members should have the autority to influence contributions towards e.g. running in-person User Meetings.

**Responsibilities specific to all UCWG Members.**

* Provide and maintain resource levels on agreed user communication items.
* Facilitate User Meetings.
* Facilitate Coffee with Scientists and Users or similar purpose discussions

**Responsibilities of the UCWG Chair.**

* The chair will act as “Lead Coordinator” of the overall direction and health of this WG.
* Resolving conflicts which cannot be resolved by consensus.
* Calling regular meetings of the WG (the Secretary might do this instead).
* Attend User Meetings

**Responsibilities specific to the UCWG.**

* Communicates relevant items on local facility management and vice versa.
* Overseeing, resourcing and scheduling User Meetings.

**Operations specific to the TWG**

* The WG will meet ??? online.
* The WG will meet face-to-face at least ???.
* The WG organises the face-to-face User Meetings and (optionally) virtual User Meetings.


   
3.2? Governance Model Reviews and the GMWG
--------------------------------------------

* Coordinate the review of the governance model (this document and associated documents).

The Steering Committee will be responsible for the review of the governance of the Mantid project at a suitable frequency.
This will be coordinated by the chairs of the Technical and Scientific Working Groups.
Key elements of this review process will include:
* External reviewers where appropriate.
* An evaluation of whether the governance is facilitating or hindering collaboration.
* Updates to the governance in the spirit of continuous improvement.


3.? Developer Workshop
----------------------

This annual face-to-face meeting is organised by the Technical Working Group (TWG) and is optionally organised alongside the User Meeting.
There may also be additional virtual Developer Workshops throughout the year.
The TWG is responsible for creating an agenda for the meeting.

The purpose of the Developer Workshop is as follows:
* Promote interaction between developers, from both Contributing Facilities and Individual Contributors.
* Run code camps to work on backlog issues (defined by the TWG) or issues that benefit from a more interactive approach to problem solving.
* Discuss new technologies and infrastructures which may be leveraged to enhance the project.
* Gather feedback on day-to-day working practices and identify points for improvement.
  
User Meeting
----------------

This recurrent (e.g. annual or biannual) face-to-face meeting is organised by the User Communication Working Group (UCWG) and is optionally organised alongside the Developer Workshop.
There may also be additional virtual User Meetings throughout the year.
The UCWG is responsible for creating an agenda for the meeting.

The purpose of the User Meeting is as follows:
* Promote communication and connection between contributors and users of Mantid and the applications produced using the Mantid framework.
* Include updates from each Contributing Facility.
* Include update from the Technical Working Group (TWG).
* Include recent news and individual presentations (via talks or posters).
* Consider including themes that focus on specific topic areas relevant to the Mantid collaboration.
* Consider discussing new technologies/infrastructures which may be leveraged to enhance the user experience.

Coffee with Scientists and Users
--------------------------------

Purpose or these or similar is sharing between instrument scientists on early ideas and committed work items with a science focus. with the benefit to add additional value to the collaboration by ....

In more detail, WG focussed for scientists to informally meet and discuss scientific ideas and needs for Mantid:
* Before one or more facilities have committed resources to such ideas and by extension are already visible on the CCR. Purpose is to bounce ideas early, help to identify early if an idea deserve further consideration early, if it is specific on one facility or not, how scientific validation could be careered out etc 
* Discussion of upcoming new scientific work items on the CCR and the potentially use of such to instruments more broadly

Appendix: Example for interaction from a Contributing Facility
==============================================================

**ISIS local arrangement**
The diagram below provides ISIS-specific detail on the interaction with the wider collaboration governance.
This represents a concrete example  of how a facility might interact with the collaboration-wide governance.
ISIS has internal Mantid Programme Board which includes science representatives from each of ISIS's science divisions, product manager and the ISIS Mantid team lead who prioritises large mantid needs in the form of Epics, some of which make it Ready state, which means ISIS says they are needed for ISIS and ready to moved into implementing in approximately the order prioritised. Those in Ready that are the ISIS Mantid team know they can commit to within the next releases the ISIS Mantid Team lead bring to the TWG. Vice versa the Mantid Team lead share information with the ISIS MPB about identified large Mantid framework work that are needed to keep Mantid deployable such as devops changes and large 3rd party dependences (e.g. Qt5->Qt6) 

Update out of date figure below
![isis-internal-governance](static/images/isis-internal-governance-example.png)


**ILL local arrangement**
The diagram below shows the local ILL implementation with respect to the steering committee (Mantid Collaboration):

![ill-internal-governance](static/images/ill-internal-governance-example.png)
