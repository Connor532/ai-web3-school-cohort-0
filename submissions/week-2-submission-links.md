# Week 2 Submission Links

Use these public GitHub links after committing and pushing the Week 2 files.

## Main Week 2 Package

- Week 2 total delivery / proposal: https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/tasks/week-2-direction-proposal.md
- Daily note: https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/daily/2026-05-30.md

## Task-specific Links

| Course Task | Suggested Submission Link |
| --- | --- |
| Week 2 Direction Research / Problem Map | https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/tasks/week-2-problem-map.md |
| Week 2 Payment / Commerce Flow | https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/tasks/week-2-payment-commerce-flow.md |
| Week 2 x402 Paywall + CAW Design | https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/tasks/week-2-x402-caw-design.md |
| Week 2 Agent Identity Profile | https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/tasks/week-2-agent-profile.md |
| Week 2 Wallet / Permission Strategy | https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/tasks/week-2-agent-wallet-permission-strategy.md |
| Week 2 Security / Privacy Threat Model | https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/tasks/week-2-agent-threat-model.md |
| Week 2 Governance / Coordination Workflow | https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/tasks/week-2-governance-coordination-workflow.md |
| Week 2 Total Delivery / Proposal | https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/tasks/week-2-direction-proposal.md |

## Copy-ready Submission Notes

### Direction Research

I mapped six AI x Web3 directions: payment/commerce, agent identity, wallet permission, privacy/security, dev tooling, and governance/coordination. I selected restricted agent payment and delivery workflow as my Week 2 main direction because it requires both AI task understanding and Web3 payment/permission/verification mechanisms. No sensitive information is included.

### Payment / Commerce

I designed a minimum agent commerce flow where a user sets a budget, a buyer agent requests a quote, a service agent delivers work, a verifier checks the result, and payment/refund/dispute records are stored. The design includes quote, budget authorization, execution, delivery, verification, settlement, and proof records. No real payment credentials or wallet secrets are included.

### x402 + CAW Advanced Design

I submitted an architecture sketch for an x402 paywall plus CAW/Pact-style restricted payment loop. It shows how an agent receives a 402 payment requirement, checks the amount/recipient/network/resource against policy, pays only if allowed, and records an auditable receipt. This is a design/pseudocode submission, not a real-fund demo.

### Agent Identity

I drafted a `ProofPack Research Agent` profile, including identity, maintainer, capabilities, inputs/outputs, payment sketch, verification method, and failure points. It compares MCP, ERC-8004, and x402/ERC-8183 as different layers for tools, identity, and commerce.

### Wallet / Permission

I designed a restricted agent wallet strategy with budget caps, allowed networks, allowed contracts, executable actions, human confirmation thresholds, revocation paths, logs, and failure handling. It explains why ERC-4337, Safe, and guard/policy mechanisms matter for limiting agent risk.

### Security / Privacy

I wrote a threat model for a restricted buyer agent workflow, covering wallet authority, budget policy, private context, payment receipts, delivery results, and public proof records. It includes risks such as prompt injection, forged tool results, payment swaps, over-broad approvals, data leakage, and mainnet confusion.

### Governance / Coordination

I designed a meeting-to-action workflow for DAO/community coordination. AI can summarize notes and draft action items, but proposal approval, budget movement, public commitments, votes, and multisig execution must remain human/governance confirmed.

### Total Delivery

I submitted a Week 2 direction deep-dive and initial project proposal for `ProofPay Agent`, a restricted agent payment and delivery workflow for small digital services. It includes problem map, main direction, participants, flow diagram, AI/Web3 roles, automation boundary, proposal, risks, validation plan, references, and backlog.

## Safety Boundary

These links and notes do not include private keys, seed phrases, API keys, tokens, `.env` files, private course links, or real-asset account information.
