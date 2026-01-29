# Name

Coordinating Agent To Agent List of efforts (CATALIST)

## Description 

This is a non-WG-forming effort to coordinate among the various initiatives to develop IETF work on AI agent-to-agent communications.

Over the last several IETF meetings, there have been numerous side meetings focused on agent-to-agent communications, particularly for AI agents. The scheduling conflicts with regular IETF agendas have made it difficult for participants to follow all of these meetings.

This BoF provides an opportunity to:

- Summarize the ecosystem, including work occurring outside the IETF at W3C, 3GPP, and the Linux Foundation
- Summarize work occurring in IETF side meetings and progressing on mailing lists.
- Identify what work should be pursued in the IETF.
- Identify and share existing IETF working groups that are addressing use cases related to agent communication.

CATALIST is explicitly not intended to select between competing proposals, nor to prematurely define any end-to-end agent communication protocols. Instead, the meeting will provide a forum to share information about these efforts and to determine whether any recurring meeting would be useful for coordination purposes.

This BoF is not intended to replace discussions at side meetings, which can continue to be useful for developing and discussing ideas in detail. The meeting is intended to provide a high-level overview and to determine what would be helpful to the IETF community regarding trends in AI and agent communication.

This BoF is not for AIProto or DMSC, which are evolving on their own mailing lists; it is for discussing the overall ecosystem and the needs of the community.

### Scope Focus: Agent-to-Agent (A2A) Communication
This proposal focuses exclusively on the requirements, protocols, and architecture for communication between AI agents, specifically:

- **Discovery and Interoperability:** Enabling agents built on disparate protocols to find and interact with one another
- **Agent-to-Agent Architectures:** Standardizing the interfaces and interaction models between independent AI agents

### Out of Scope
The following topics are considered out of scope for this BoF:

#### Networking for AI (Net4AI)
Optimizing network infrastructure to support AI workloads. This includes:

#### Traffic Engineering: Provisioning of pipes, load sharing, and traffic steering

#### Compute Coordination: Mechanisms to arrange or share processing loads during AI training
Primary Venues: Work typically addressed in the RTG area

#### AI for Networking (AI4Net)
Using AI/ML techniques to manage or optimize network operations. This includes:
- **Operational Logic:** Telemetry collection, data distribution, and fault correlation/prediction
- **Network Management:** Using AI to automate or operate the network
- **Primary Venues:** Work typically addressed in OPS, NMRG, RTG, and INT

## Required Details

**Status:** Not WG Forming

**Responsible Area:** ART. WIT, SEC, INT, OPS, and RTG have an interest

**Responsible ADs:** Andy Newton, Orie Steele, Charles Eckel (incoming)

**BoF chairs:** 
- Adrian Farrel <adrian@olddog.co.uk>
- Yingzhen Qu <yingzhen.ietf@gmail.com>

**BOF proponents:**
- Toerless Eckert <tte@cs.fau.de>
- Kehan Yao <khyao78@gmail.com>
- Aijun Wang <wangaijun@tsinghua.org.cn>
- Suresh Krishnan <suresh.krishnan@gmail.com>

**Number of people expected to attend: 200**

**Length of session: 2 hours**

**Conflicts (whole Areas and/or WGs)**
- Chair Conflicts: TVR, RTG Area Open Meeting, CATS, MPLS, TEAS, LSR, RTGWG, 6MAN, Dispatch, OPSAWG, PCE
- Technology Overlap: ART, WIT
- Key Participant Conflict: All ART Area, CATS, IDR, ANIMA, IAB, ANRW, IOTDir, BPF, AICONTROL, AIPref

## Information for IAB/IESG

Several recent side meetings have discussed Agent-to-Agent communication, including meetings at IETF 123 and 124. See [References](#relevant-i-ds-and-links) below for the side meeting Trello URLs and individual proposal mailing lists.

The IESG has created the agent2agent@ietf.org mailing list for coordination and discussion of this topic.

The session should be scheduled as early as possible in the week to allow questions raised or suggestions made to be discussed during side meetings later in the week at IETF 125.

## Tentative Agenda

- Administrivia (chairs) [5 minutes]
- Purpose of BoF (chairs/AD) [5 minutes]
- Summary of efforts and their scope [60 minutes]
  - For each effort, present:
    - Main purpose and direction
    - Summary of mailing list discussions
    - *Note: Short summaries only, not deep discussions*
    - *Questions should be for clarification only*
  - Side meetings at IETF 123 and 124, including:
    - "AI Agent Protocols" (AIProto)
    - "AI Network"
    - "AI Agent Discovery"
    - "AI-Agent Network Requirements and Protocols" (ANP)
    - "Distributed Micro Services Communication" (DMSC)
    - "IoA@Enterprise" (ACIP - Agent Communications Internet Protocol)
    - Other related initiatives
  - Work outside the IETF: W3C, 3GPP, and the Linux Foundation

- Open discussion [40 minutes]
  - What broad topics belong in the IETF scope?
  - What coordination activity would be useful?
    - Would a coordination working group (similar to MOPS, IoTOPS, or PQUIP) be useful?
    - Would similar future meetings be useful?

- Closing remarks and next steps (chairs and AD) [10 minutes]

## Relevant I-Ds and Links

### Side Meetings

IETF 123 and IETF 124 side meetings:
- https://trello.com/b/6kmZPwOx/ietf-123-side-meeting-scheduling
- https://trello.com/b/s1hNprRf/ietf-124-side-meeting-scheduling

### Mailing Lists

**agent2agent@ietf.org** (https://mailman3.ietf.org/mailman3/lists/agent2agent@ietf.org/)

Non-working group mailing list created by the IESG to coordinate and exchange information on possible areas for standardization related to AI agents. Topics include:
- Standardized ways for AI agents to discover each other
- Discovery of resources such as APIs and documents
- Protocols for agent-to-agent communication

**dmsc@ietf.org** (https://mailman3.ietf.org/mailman3/lists/dmsc@ietf.org/)

Non-working group mailing list exploring solutions for comprehensive communication architecture that enables secure and efficient collaboration between heterogeneous AI agents. The list focuses on defining function modules, interoperable protocols, and mechanisms that enable AI agents to collaborate effectively to accomplish complex tasks. This list may result in proposing a BoF, side meeting, or IAB Workshop.

### Draft Charters

- [AIProto draft charter](https://github.com/jdrosen/aiproto-wg/blob/main/charter.txt)
- [DMSC draft charter](https://github.com/ietf-dmsc/Charter/blob/main/dmsc-charter.md)

### Repository

The CATALIST BoF will provide a shared repository where proponents of related initiatives can summarize their work and link to relevant home pages, key documents, and supporting information (e.g., drafts, GitHub repositories, mailing lists, and slide decks).
