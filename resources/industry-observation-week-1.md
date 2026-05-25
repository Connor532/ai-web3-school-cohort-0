# Week 1 Industry Observation: AI x Web3 Projects

## Goal

Pick 1-2 AI x Web3 related projects or directions and describe their positioning, users, technical direction, and connection to Week 1 concepts.

## Project 1: Hermes Agent

Link:

https://hermes-agent.nousresearch.com/docs/

### Positioning

Hermes Agent is an agent framework direction focused on tool use, memory, skills, and longer-running agent workflows.

### Possible Users

- Developers experimenting with autonomous or semi-autonomous agents
- Researchers comparing agent frameworks
- Builders who want reusable skills and persistent task workflows

### Week 1 Connection

Hermes connects directly to these Week 1 AI concepts:

- Agent
- Tool Use
- Workflow
- Skills
- Memory
- Human-in-the-loop review

### AI x Web3 Angle

For Web3, an agent framework could help prepare transaction explanations, summarize contract calls, maintain learning logs, or guide testnet practice. But it should not directly own private keys or execute wallet actions without explicit human confirmation.

### Open Questions

- How should Web3-specific tools expose safe permissions to an agent?
- How can an agent record every action in a way that is easy to audit?
- Where should the handoff happen between agent suggestion and wallet confirmation?

## Project 2: Safe / Smart Account Direction

Link:

https://docs.safe.global/home/overview

### Positioning

Safe is part of the smart account and multisig infrastructure direction. It focuses on account security, shared control, and programmable account behavior.

### Possible Users

- Teams managing shared assets
- DAOs and public goods projects
- Projects that need stronger approval workflows
- Builders exploring smart account patterns

### Week 1 Connection

Safe connects to these Week 1 Web3 concepts:

- Wallet
- Smart account
- Multisig
- Signature
- Transaction
- Permission boundary

### AI x Web3 Angle

Smart accounts and multisigs are important because AI agents need limited, inspectable, and revocable permissions. Instead of giving an agent broad private key control, builders can design workflows where AI drafts or recommends actions while humans or account rules approve execution.

### Open Questions

- What permissions should an AI assistant get by default?
- How should spending limits, allowlists, and expiry be shown to users?
- How can AI-generated transaction summaries avoid hiding important risk?

## Personal Takeaway

The AI x Web3 opportunity is not simply "let AI control a wallet." The more useful direction is controlled delegation: AI can help understand, prepare, simulate, summarize, and record actions, while wallet permissions and human confirmation define the execution boundary.

