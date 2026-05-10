# ENS Builder Grant Application

**Title***
Built Different: ENS Identity Layer for Autonomous AI Agents

**Description*** *(1500 / 1500 characters)*
**Built Different** is a Web3 x AI R&D Lab based in Harare, Zimbabwe. Our 6-month intensive accelerator trains local developers to build agentic dApps powered by Ethereum
As AI agents become autonomous actors capable of writing code and deploying smart contracts, they face a severe trust deficit. How do we distinguish legitimate agents from bots? How do we prove an agent actually generated a specific artifact?

Archie AI (piloted at the Built Different R&D Lab in Harare) integrates ENS as the foundational identity, reputation, and coordination layer for autonomous AI agents. Our implementation moves ENS beyond cosmetic naming by embedding it directly into the agent lifecycle:

1. Dynamic Instantiation: Deployed agents (e.g., smart contract auditors) receive embedded dynamic wallets and are assigned human-readable ENS subnames (e.g., `auditor.archie.eth`).
2. Verifiable Provenance: To combat AI hallucinations, our agents anchor their work onchain. Every generated artifact (system architecture, code, audit) is cryptographically hashed, and the hash is stored as a verifiable ENS text record on the agent’s profile. This creates a tamper-proof portfolio for non-human workers.
3. Agent Coordination: Agents use ENS text records to store capabilities and resolve addresses, enabling decentralized multi-agent workflows.

This project transforms ENS into a verifiable credentialing system for AI, proving that ENS can do the "real work" of agent discovery and cryptographic proof-of-work.

---

### Planned Milestones

#### Milestone 1

**Description**
Integrate deep ENS fundamentals into the Built Different R&D Lab's core 6-month accelerator curriculum. Utilizing the official ENS documentation and recognized best practices (the ENS source of truth), we will comprehensively train our cohort of developers. This ensures the next generation of African builders are native practitioners who default to ENS for decentralized identity and naming schemas before they even begin building agentic dApps.

**Detail of Deliverables**

- A dedicated ENS educational module embedded within the accelerator curriculum based on official ENS resources.
- Live workshops and training sessions for the initial cohort covering ENS architecture, resolution, text records, and subname issuance.
- Verifiable credentialing for students upon completing the ENS module.

**Requested Funds (in ETH)**
0.5 ETH

---

#### Milestone 2

**Description**
Develop the core infrastructure to programmatically assign ENS subnames to newly instantiated AI agents. This involves integrating embedded wallets to automatically provision onchain accounts for agents, and interacting with the ENS Public Resolver to register subnames (e.g., `engineer.archie.eth`) upon deployment, giving each agent a persistent human-readable identity.

**Detail of Deliverables**

- Helper functions and contract logic for programmatic ENS subname registration tied to agent wallets.
- Backend integration within the Archie AI platform to trigger subname claiming during agent creation.
- A functional frontend UI component where users configure their agent's ENS identity before deploying it onchain.

**Requested Funds (in ETH)**
0.5 ETH

---

#### Milestone 3

**Description**
Implement the cryptographic anchoring mechanism to store agent outputs as ENS text records, turning the ENS profile into a verifiable portfolio. We will also define an ENS metadata schema that stores agent capabilities, allowing other agents to query ENS, resolve addresses, and verify the authenticity of AI-generated code before interacting with it.

**Detail of Deliverables**

- Keccak256 hashing integration for agent-generated artifacts (e.g., Solidity code, system architecture diagrams).
- Automated transaction builders that update the agent's ENS text records with these artifact hashes via the Public Resolver.
- Open-source repository containing the agent integration code.
- A live showcase video demonstrating agent instantiation and onchain ENS verification.

**Requested Funds (in ETH)**
0.5 ETH

---

#### Milestone 4

**Description**
Develop the "Agent-to-Agent Coordination" layer using ENS as the discovery protocol. We will implement the logic required for one autonomous agent to locate another by resolving its ENS subname, verifying its capabilities via text records, and automatically initiating a handoff or workflow (e.g., a Builder agent dynamically finding an Auditor agent).

**Detail of Deliverables**

- An agent-side discovery API to search and query ENS records based on required capabilities.
- A functional multi-agent workflow demonstration where one agent autonomously parses another agent's ENS text records.
- Integration of the agent capability metadata schema directly into the ENS registry.

**Requested Funds (in ETH)**
0.5 ETH

---

**Total requested funds:**
2 ETH

**Showcase Video Url***
https://youtube.com/shorts/PD_bCufgaW4

**Github***
https://github.com/TheGodOfAwesome/Ethereum-Community-Hub-Harare

**Email address***
kmuvezwa@gmail.com

**Project or personal twitter***
https://x.com/builtndifferent

**Telegram handle***
@kuzivakwashem
