# Mantid Collaboration Governance Model

Purpose of this document
========================

This document describes the governance framework for the Mantid Collaboration.
The history of the governance is stored in the [history file](history.md).

(The key aims of this governance model are: i.e. explain what is purpose is!)

Governance Structure
====================

This section describes the revised governance structure for the Mantid Collaboration (starting in 2026?).
Figure 1 shows a representation of the cross-facility Working Groups at the collaboration wide level, and its interaction of with contributing facilities.

The box labelled "Each Contributing Facility" represents a simplified map of the stakeholders at any research facility that acts as a Contributing Facility.
These include facility scientists and Mantid developers and facility users, and "board" of some kind that oversee and prioritise Mantid needs for a single facility. The latter will vary from a single developer and one or more scientists meeting informally to discuss prioritise and needs to a formal board meeting on a regular cadence to discuss and prioritise Mantid requirements across 20+ instruments. The Mantid governance model does not perscribe how such a "board" is setup or run, but assume there is some form of local setup such one person from this setup will be attending the recurrent Technical working group (TWG) meetings.

One role of the TWG is to keep up date a Committed Mantid Roadmap. This roadmap will contain large work items that are needed to keep Mantid operational and deployable on the OS platforms that facilities requires it to run on, and any new user capabilities that one or more facilities have committed resources for and the TWG have been informed about.

More specifically the Collaborative components of the model are:

* Technical Working Group (TWG) - maintain and update a Committed Roadmap and responsible for running Mantid Developer Workshops
* User Communication Working Group (UCWG) - cover user communication not covered by other means and the facilitation of [User Meetings](#user-meeting) and optionally Coffee thing 
* Optional: Governance Model Working Group (GMWG) - its purpose is to periodically review and update this document and governance model, including to check that it is not become out-of-date. This is meant to a WG in the lighted sense possible, periodically (e.g. yearly) review and update this governance model, with option to feed in ideas ongoingly.

Examples of local facility management and how it will interact with the Collaboration governance are given in the Appendix.

![steering-committee-facility](static/images/steering-committee-facility-interaction.png)

**Fig 1. Representation of the interaction between the Mantid governance and stakeholders in Contributing Facilities. The nominal limit of Steering Committee size is implemented as an initial way of working that will be adapted as necessary.**

The governance structure is developed to stimulate collaboration, where appropriate, resulting in open source code base or common code and that is developed and maintained in a collaborative way.
This model allows individual facilities to develop Mantid according to their own requirements, with accountability for delivery and resource management to their own executive management, while leverage collaboratively working where this is of mutually beneficial.

The leading philosophy of Mantid development is that:
* The Mantid Collaboration seeks to coordinate individual contributions to a free open source software (FLOSS) project.
* Facilities (Facilities in this context refers to research infrastructures such as ISIS, SNS and ILL) act as contributors to an open source software development.
This document refers to such facilities as "Contributing Facilities".
  * Mantid is open to new Contributing Facilities providing that those facilities agree to the terms listed below and can commit their own resources to develop the framework for their needs.
* Individual contributors are welcome and do not need to be part of the formal organisation or a member of a facility.
They are referred to in this document as “Individual Contributors”.
  * Becoming an Individual Contributor is an open process which is defined at a technical level by the workflow for contributing code.

In this model the term Contributors refers to a facility or group that contributes to the Mantid development. The Collaboration also welcome Guests including to learn more about the Collaboration before considering requesting membership.

**Contributing Facilities shall**
* Resource the development according to the required use by the facility (i.e. each Contributing Facility will have sufficient level of effort available to resource their own specific development of Mantid. As such the collaboration is a do-ocracy, in a similar way to other scientific software developments such as SASView (https://www.sasview.org/).).
* Provide own local management, requirement gathering process and development.
* Nominate members to the non optional Working Groups.
* Help Mantid products remain FLOSS.
* Adhere to the development workflow and standards for code quality set out by the TWG.
* Contribute to maintenance and testing activities.
* Be open to suggestions and feedback from Individual Contributors to the project.

**Contributing Facilities should**
* Contribute to infrastructure costs.
* Maintain a level of effort, expertise or capability in Mantid.
* Host (and fund) the annual User Meeting and Developer Workshop.

General to all Working Groups.
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
* An elected Secretary. The secretary can be a non voting member, in this regard, in the same way a guest.

**Responsibilities of the WG Secretary.**

* Calls regular meetings of the WG with agendas (if this is not done by the chair).
* Writes meeting minutes with records of decisions made and brief high-level summary of discussions. Minutes should be comprehensible by other Mantid developers.

**General Responsibilities of all members of the WGs.**

* Communicate the facility’s interests and intentions to the WGs.
* Communicate WG discussions and outcomes to their facility management.
* Be open to discussion of topics and work towards solutions that foster commonality through consensus.
* Be open to receive request from self-nominated guests and open to invite guests to join WG meetings, informing the WG chair ahead of meetings guests attend.
* Attending the WG meetings regularly or sending a delegate where this is not possible.

**General Responsibilities of each WG.**

* Hold a public accessible list of its members, and optionally Individual Contributors.
* Hold recurrent meetings with publicly circulated agendas and meeting minutes with records of decisions made.

**Operation common to all WGs.**

* Each WG will meet on a regular cadance.
* Each WG will elect a Chair from within the existing membership. The position of Chair is for a fixed term appointment, reviewed annually by the WG.
* Each WG will elect a Secretary that can be a person external to the WG. The position of Secretary is for a fixed term appointment, reviewed annually by the WG.
* Keep its membership list up to date.
* Make agenda and minutes of WG meetings publicly accessible.
* The WG can be contacted by anyone outside the Collaboration via a mailing list (where such exists, see individual WG sections), or by reaching out to the chair or other WG members on the membership lists.

Below is an example of how the frequency of WG meetings could be (as of Nov 2025, this is how these are run for the TWG).

| Jan  | Feb  | Mar  | Apr  | May  | Jun  | Jul  | Aug  | Sep  | Oct  | Nov  | Dec  |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| GMWP |      |      |      |      |      |      |      |      |      |      |      |
| TWG  | TWG  | TWG  | TWG  | TWG  | TWG  | TWG  | TWG  | TWG  | TWG  | TWG  | TWG  |
|      |      | SCWG |      |      | SCWG |      |      | SCWG |      |      | SCWG |

*Table 1: An example frequency of meetings for the collaborative Working Groups. The cadence of User Meetings and Developer Workshops are determined by the SCWG and TWG respectively. In terms of in-person Developer Workshops running these yearly or similar is strongly encouraged, where these historically have provided strong benefits for the collaboration. Similarly in-person User meeting have been very beneficial (including the Nov 2025 meeting) and it is highly recommended (e.g. from the Nov 2025 User meeting) to periodically run such e.g. yearly. Historically, in-person developer and user meetings have run side by side although there is no requirement that they are. In addition virtual versions of developer and user meetings are encouraged.*

3.3? Process for Resolving Conflicts
-----------------------------------

In the unlikely event where the collaboration has reached an impasse, members will resort to the use of a third party conflict resolution process.
The chairs of the Scientific and Technical Working Groups will be responsible for invoking this resolution procedure.
The pair will document the issue/s and prepare a summary which will be sent to all participating facility directors.
The facility directors will then be invited to assume a mediation/arbitration role in a joint Steering Committee meeting which comprises the combined Scientific and Technical Working Groups.
The conflict will be presented to facility directors in detail providing each interested party to state their case.
If directors are unable to mediate a resolution, they will arbitrate the dispute and force a final decision thus providing a way out of deadlock.
The need for this conflict resolution is expected to happen very infrequently, and since the introduction of the 2021 Governance model and now, Nov 2025, it has not been invoked.

3.4 Technical Roadmap Working Group (TWG) and the Committed Collaborative Roadmap (CCR).
----------------------------------------------------------------------------------------

The Technical Working Group (TWG) owns the Comitted Collaborative Roadmap (CCR) and the Developer Workshops (for the collaboration).
It coordinates technical discussions and discussion related to items/topics on the roadmap, with an emphasis on those that concerns multiple faciliities.

**Committed Collaborative Roadmap (CCR).**

The CCR is composed of broadly two following two catagories of work items/topics: 

* (large) work items needed to keep Mantid operating and being fit for the the future. For example, existtential work to keep up to date with 3rd party dependencies such as Python and Qt, keep the development pipeline functional, keep Mantid deployable on relevant platforms, keep a tap on technical debt, handle future instrument data rate and read/write rates, security etc. Individual facilities built their roadmaps at each facility to identify their local needs. The wider Collaborative roadmap is structured as a set of topics for which one or more Contributing Facilities will assign resources (or in the case of an Individual Contributors, will undertake the work). In addition, discussions between TWG members may identify new existential Mantid needs that in return TWG members will communicate back to individual facility management board/committees/other, to stimulate awareness of such and stimulate discussions on resource implications. When resource from one or more facilities has been committed to such work the corresponding item ges associated with a future release on the CCR.
* (large) work items to enhance Mantid with new capabilities such as to handle of new instruments and instrument upgrades, improving the scientific accuracy of data reduction for a specific technique, support of new type data reduciton, user usability needs etc. as needed by individual facilities. Work items of this kind only appear on the CCR once at least one facility has committed resources to do the work. By making such work visible on the CCR the whole collaboration can see what is upcoming. As an optional bonus other facilities may volunter to contribute to such works. For instance, with additional scientific validation testing, PR review testing and/or direct coding contributions.  Scientific technique areas include: Powder diffraction, Single crystal diffraction, Engineering diffraction, Disordered materials, Small angle neutron scattering (SANS), Reflectometry, and Spectroscopy (Direct geometry, Indirect geometry, Triple axis spectrometer, Neutron spin echo, Deep inelastic, Quasi-elastic neutron scattering (QENS), Muon spin rotation).

There will naturally also be topics that might be argued to into both of the above two catagories such as: Mantid specific needs to help support external live streaming infrastructure or other facility software infrastructures, cross-cutting instrument geometry changes, deprecation or support for compatibility with new 3rd party software interfaces.

Work on applications that leverage Mantid (e.g. as a library) and are outside of the Mantid collaboration will not be listed on the CCR. 

The roadmap is managed using Agile with a kanban-style representation. It is reviewed at each of the regular meetings of the Working Group.
This visual style is aimed at facilitating effective communication of the current status, complexity and interdependencies.
Topics in the roadmap are detailed enough to foster communication, while broad enough to be relevant to multiple contributors.

Example roadmap topics include:
* File loading performance for neutron event data.
* Live streaming and infrastructure.
* Instrument geometry rendering.
* Data structure performance.
* Compatibility with external software ecosystems (e.g. pandas or PACE).
* Componentization of scientific interfaces
* Other applications such as imaging or auto-reduction which do not sit within data reduction as such.

For information applicaable to all WGs see [here](#general-to-all-working-groups).

**Membership info specific to the TWG.**

Nominated members should be senior technical staff who are involved in local core Mantid work and/or local facility Mantid team leads and/or have oversight over local facility Mantid roadmap needs.
Members must have the authority to discuss and agree the contributions to the collaboration roadmap.

**Responsibilities specific to all TWG Members.**

* Provide and maintain resource levels on agreed roadmap items.
* Communicate changes in priorities at local facilities which may affect the overall technical roadmap.
* Facilitate and attend Developer Workshops.
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
