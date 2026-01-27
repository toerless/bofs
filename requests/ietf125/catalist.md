# Name

Coordinating Agent To Agent List of efforts (CATALIST)

## Description 

Non-WG-Forming effort to coordinate among the many attempts to develop IETF work around AI agent-to-agent communications.

Over the last few IETF meetings there have been a considerable number of side meetings focused on agent-to-agent communications (especially for AI agents). 
It was hard for IETF participants to follow all of these meetings especially considering conflicts with the regular IETF agendas.

This BoF provides an opportunity to:

- Briefly summarize the ecosystem, including work happening outside of the IETF, at W3C, 3GPP, and the Linux Foundation.
- Briefly summarize work that is happening in IETF side meetings and that is progressing on mailing lists (specifically DMSC and AIProto).
- Answer questions like what work should be pursued in the IETF?
- Identify and share existing IETF WGs that are already addressing some of the use cases tangent to agent communication.

CATALIST is explicitly not intended to pick between competing proposals, nor to prematurely define any end-to-end agent communication protocols. 
Instead, the meeting will provide a forum to share information about these efforts and to offer the community an ability to see if any kind of recurring meeting is useful for coordination purposes.

Note that this BoF is not intended to squelch discussions at side meetings which can continue to be useful to develop and discuss ideas in detail. 
The meeting is meant to provide a high level overview, and to figure out what would be helpful to the IETF community regarding trends in AI & Agent communication.

This BoF is not for AIProto or DMSC which are evolving on their own mailing lists: it is for discussing the overall ecosystem and the needs of the community.

## Scope Focus: Agent-to-Agent (A2A) Communication

This proposal focuses exclusively on the requirements, protocols, and architecture for communication between AI agents, specifically:

* **Discovery and Interoperability:** Enabling agents built on disparate protocols to find and interact with one another.
* **Agent-to-Agent Architectures:** Standardizing the interfaces and interaction models between independent AI agents.

## Out of Scope

The following topics are considered out of scope for this BoF:

### 1. Networking for AI (Net4AI)

Optimizing network infrastructure to support AI workloads. This includes:

* **Traffic Engineering:** Provisioning of pipes, load sharing, and traffic steering.
* **Compute Coordination:** Mechanisms to arrange or share processing loads during AI training.
* **Primary Venues:** Work typically addressed in the **RTG** area.

### 2. AI for Networking (AI4Net)

Using AI/ML techniques to manage or optimize network operations. This includes:

* **Operational Logic:** Telemetry collection, data distribution, and fault correlation/prediction.
* **Network Management:** Using AI to automate or operate the network.
* **Primary Venues:** Work typically addressed in **OPS**, **NMRG**, **RTG**, and **INT**.

## Required Details

Status: Not WG Forming

Responsible Area: ART. WIT, SEC, INT, OPS, and RTG have an interest.

Responsible ADs: Andy Newton, Orie Steele

BOF proponents:
   Adrian Farrel <adrian@olddog.co.uk>
   Toerless Eckert <tte@cs.fau.de>
   Kehan Yao <khyao78@gmail.com>
   Aijun Wang <wangaijun@tsinghua.org.cn>
   

Number of people expected to attend: 200

Length of session: 2 hours

Conflicts (whole Areas and/or WGs)
   Chair Conflicts: TBD
   Technology Overlap: ART, WIT
   Key Participant Conflict: MPLS, CATS, ANIMA

## Information for IAB/IESG

Several recent side meetings discussed Agent-to-Agent communication, including the following from IETF 123 and 124 
IETF123: https://trello.com/b/6kmZPwOx/ietf-123-side-meeting-scheduling
IETF124: https://trello.com/b/s1hNprRf/ietf-124-side-meeting-scheduling

Mailing lists discussing AI & Agent communication:
- https://mailman3.ietf.org/mailman3/lists/agent2agent@ietf.org/
- https://mailman3.ietf.org/mailman3/lists/dmsc@ietf.org/

We suggest the session be held as early as possible in the week, as several questions raised will be discussed during side meetings during IETF 125.

## Agenda

- Administrivia (chairs) [5 mins 05/120]
- Purpose of BoF (chairs/AD) [5 mins 10/120]
- Summary of efforts and their scope. [60 mins 70/120]
  - Outside the IETF, at W3C, 3GPP, and the Linux Foundation.
  - Side meetings at IETF 124 and 123 and other IETF efforts.
    - AIProto
    - DMSC
    - DNS-based agent discovery
      
    - What to cover
      - What is the main purpose/direction of the effort.
      - What has happened in mailing list discussions.
      - Short summaries, not deep discussions.
      - Questions only for clarification.
- Open discussion [40 mins 110/120]
  - What broad topics belong in the IETF scope?
  - What coordination activity would be useful?
    - Is a coordination working group (like MOPS / IoTOPS / PQUIP) useful?
    - Would it be useful to have similar future BoF meetings?
- Closing remarks and next steps (chairs and AD) [10 mins 120/120]

## Relevant I-Ds and Links

The agent2agent@ietf.org mailing list discusses possible areas for standardization related to AI agents.
These include: 
- standardized ways for AI agents to discover each other, 
- to discover resources like APIs and documents, 
- to converse with each other, and so on.

The dmsc@ietf.org mailing list is to explore solutions for the comprehensive communication architecture that enables secure and efficient collaboration between heterogeneous AI agents, defining function modules, their interoperable protocols and mechanisms that enables AI agents to collaborate effectively to accomplish complex tasks.
- This list discusses possible areas for standardization related to AI agents. 
- The list might result in proposing a BoF, a side meeting or an IAB Workshop. 

Further links to be added depending on agenda items, but see list of prior work above.

We will also work on creating a wiki.ietf.org page for tracking the coordination effort. 

This will provide a shared repository where proponents of related initiatives can briefly summarise their work and link to the relevant home pages, key documents, and other supporting information (e.g., drafts, GitHub repositories, mailing lists, and slide decks).
