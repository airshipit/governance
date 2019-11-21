Airship Governance
==================

* [About Airship](#about-airship)
* [Community](#community)
	* [Join Us](#join-us)
	* [Users](#users)
	* [Contributors](#contributors)
* [Governance](#governance)
	* [Developers](#developers)
	* [Contributor](#contributor)
	* [Maintainer](#maintainer)
	* [Technical Committee](#architecture-committee)
	* [Working Committee](#working-committee)

# About Airship

Airship is a community of open source projects working to build a platform for the lifecycle management of open
infrastructure. It's designed from the ground up to make containers and Helm charts the fundamental units of software
delivery and deployment.

An Airship feeds a collection of declarative site definition YAMLs through a single front door API, and then uses them to
drive end-to-end provisioning of a site, from bare metal to fully functioning cloud.

# Community

Airship is working to build a global, diverse and collaborative community. Anyone interested in supporting the technology
is welcome to participate. We are seeking different expertise and skills, ranging from development, operations,
documentation, marketing, community organization and product management.

## Join Us

You can join our community on any of the following places:

* Visit our [website](https://airshipit.org)

* Join our [mailing list](http://lists.airshipit.org).

* Use the `irc.freenode.net` IRC server to join the discussions:
  * General/Dev discussions channel: [`#airshipit`](http://webchat.freenode.net/?channels=airshipit)

* Join our [weekly meetings](http://eavesdrop.openstack.org/#Airship_Team_Meeting)

* Get [in touch](https://wiki.openstack.org/wiki/Airship#Get_in_Touch) with us

* Follow us on [Twitter](https://twitter.com/airshipproject)

## Users

See [Airship in a bottle](https://opendev.org/airship/airship-in-a-bottle) for details on how to install Airship
inside a VM and take it for a test drive.

See [Airship Treasuremap](https://opendev.org/airship/treasuremap) for sample manifests that are CI/CD tested on real
baremetal infrastructure you can use as a starting place for your own environments.

## Contributing

See the [contributing guide](CONTRIBUTING.md) for details on how to contribute to the project.

# Governance

The Airship project is governed according to the [“four opens"](https://governance.openstack.org/tc/reference/opens.html),
which are open source, open design, open development, and open community. Technical decisions are made by technical
contributors and a representative Technical Committee. The community is committed to diversity, openness, and encouraging
new contributors and leaders to rise up.

## Developers

For code contributors, there are currently two roles relevant to project governance:

### Contributor

A Contributor to the Airship project is someone who has had changes merged within the last 12 months. Contributors are
eligible to vote in the Technical Committee elections. Contributors do not have merging rights on Airship repositories.

### Core Reviewer

A Core Reviewer has the ability to merge code into the Airship project. Core Reviewers are active Contributors and
participants in the projects.  Any Core Reviewer can nominate someone to be a Core Reviewer for a particular Airship
project, but the nominee must be approved by the existing Core Reviewers for that project. Core Reviewers are added
on an "as needed" basis determined by the core team or Technical Committee group.

## Committees

There are two committees responsible for helping to guide Airship projects:

### Technical Committee

The Technical Committee is responsible to meet and ensure Airship projects are adhering to the projects core principles,
promote standardization, define and organize the Airship versioning and release process. It is comprised of 5 members,
who are elected by an election process.

In the event of a dispute on topics falling strictly in the domain of Technical Committee responsibilities,
the Technical Committee will be responsible for abritrating. For a resolution to be confirmed, a
super majority (2/3) vote (rounded up to nearest whole number) of the Technical Committee is required.

Technical Committee elections take place in June (5 seats available). Anyone who has demonstrated a commitment to Airship
(community building, communications, or had code merged to the Airship project repositories) within the last 12 months is
eligible to run for the Technical Committee. Anyone who is a Contributor (as defined above) before the election will be
eligible to vote for the TC candidates. There are no term limits, but in order to encourage diversity, no more than 2 of
the 5 seats can be filled by any one organization. The Technical Committee will meet regularly in an open forum with
times and locations published in community channels.

The exact size and model for the Technical Committee may evolve over time based on the needs and growth of the project,
but the governing body will always be committed to openness, diversity and the principle that technical contributors make
technical decisions.

Elections take place each June. The candidates and elected members to the Technical Committee can be
found at [airship-election](https://opendev.org/airship/election).

### Working Committee

The Working Committee is intended to help influence the project strategy, help arbitrate when there is a disagreement
between Core Reviewers within a single project or between Airship projects, define the project core principles, perform
marketing and communications, and finally help provide product management as well as ecosystem support. The Working
Committee should be the group that can speak externally on behalf of Airship and to this end the Working Committee may
appoint a Lead at their own discretion and using their own process to help be a singular external voice of the project.
Representatives are expected to be active contributors who are committed to the health and success of the project. It is
comprised of 5 members, who are elected by an election process.

In the event of a dispute on topics falling strictly in the domain of Working Committee responsibilities,
the Working Committee will be responsible for abritrating. For a resolution to be confirmed, a
super majority (2/3) vote (rounded up to nearest whole number) of the Working Committee is required.

Working Committee elections take place in August (5 seats available). Anyone who is a Contributor (as defined above)
before the election will be eligible to run. Core Reviewers of projects will be eligible to vote. There are no term
limits, but in order to encourage diversity, no more than 2 of the 5 seats can be filled by any one organization. The
Working Committee will meet regularly in an open forum with times and locations published in
community channels.

The exact size and model for the Working Committee may evolve over time based on the needs and growth of the project, but
the governing body will always be committed to openness, diversity and the principle that technical contributors make
technical decisions. There is opportunity for more contributors to get involved in various sub-teams working on specific
topics, such as product management or conformance.

Elections take place each August. The candidates and elected members to the Working Committee can be
found at [airship-election](https://opendev.org/airship/election).

### Committee Elections

All elections for committee positions in Airship shall follow standard OpenStack procedures and methods. Ballots will be
distributed to each Contributor’s (or in the case of the Working Committee, Core's) primary email address. Elections will
be held using CIVS and a Condorcet algorithm (Schulze/Beatpath/CSSD variant). Any tie will be broken using Governance
TieBreaking. In the event that a candidate runs unopposed for a position, the TSC can waive a formal vote. Membership in
the Foundation itself is not a requirement for holding an elected position though it is preferred. Elections are
appointing an individual to a position in the project, not a company or organization. Individuals are expected to
continue to support the project in the event of career changes unless they notify the project that they are resigning
their position.

## Governance Changes

The project’s formal governance document is maintained in the [airship-governance](https://opendev.org/airship/governance)
repository. Changes to the document can be proposed by any project Contributor but would need to be ratified by the
Working Committee with a super-majority (2/3rds) vote. The Working Committee should strive for consensus for any change
to the project’s formal governance.

## Disputes Across Committees

Each of the Technical and Working Committees are expected to arbitrate disputes pertaining to topics that are related
strictly to those covered by the respective committees responsibilities. If a dispute arises that is unclear on
ownership of the topic, or spans multiple topics, both the Technical and Working Committees will be responsible for
working together for a resolution.  The resolution will require a super majority vote (2/3) of all committee members
(rounded up to nearest whole number).
