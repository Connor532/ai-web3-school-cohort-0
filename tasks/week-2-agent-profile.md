# Week 2 Agent Identity: Agent Profile Draft

## Agent Name

`ProofPack Research Agent`

## What It Is

`ProofPack Research Agent` is a restricted workflow agent that helps an AI x Web3 learner turn public sources, testnet actions, and GitHub notes into a structured proof-of-work pack.

It is not allowed to hold keys, sign messages, send transactions, or submit public forms without human review.

## Maintainer

- Maintainer: the learner / repo owner.
- Public home: GitHub learning repo.
- Change process: changes to capability, pricing, or permission rules must be documented in the repo.

## Capabilities

| Capability | Description | Output |
| --- | --- | --- |
| Source summarization | Summarize public docs, course prompts, and explorer pages. | Markdown note with links and caveats. |
| Proof organization | Turn task requirements into a submission checklist. | GitHub Markdown task record. |
| Wallet prompt explanation | Explain visible wallet action details in plain language. | Risk checklist, not a signature. |
| Contract interaction record | Record contract address, tx hash, function called, and result. | Public-safe task proof. |
| Proposal drafting | Draft AI x Web3 workflow or project proposal. | Markdown proposal with risk boundaries. |

## Inputs And Outputs

Example input:

```text
I deployed a MinimalStorage contract on Sepolia. Help me prepare the task proof.
```

Example output:

```text
Record the contract address, deployment tx, function called, write tx, network, explorer links, and manual confirmation points. Do not include private keys, seed phrases, API keys, tokens, or .env files.
```

## How It Is Called

- Chat request inside Codex / Claude Code / Hermes style agent.
- GitHub repo context.
- Optional public URLs such as docs or block explorer pages.
- No private wallet seed, private key, API key, or `.env` input.

## Pricing / Payment Sketch

For a future agent economy version:

- Free for local learning notes.
- Pay-per-task for structured research packs.
- Payment should be capped by a pact/policy such as `max 1 USDC per report`.
- Payment should release only after delivery passes format and link checks.

## Verification

The agent can be verified through:

- GitHub commit history.
- Public task records.
- Public source links.
- Transaction hashes and block explorers.
- A changelog of human corrections.

## Failure Points

- It may summarize a source incorrectly.
- It may miss a hidden wallet risk.
- It may overstate what a transaction proves.
- It may generate a plausible but unsupported proposal.
- It may accidentally include sensitive data if the human gives it sensitive input.

## Protocol Comparison

| Protocol | Best Fit For This Agent | Why |
| --- | --- | --- |
| MCP | Connecting the agent to tools such as files, browser, GitHub, or local scripts. | Good for tool interface and workflow execution. |
| ERC-8004 | Publishing agent identity, service metadata, reputation, and validation signals. | Good for cross-platform discovery and trust. |
| x402 / ERC-8183 | Payment and commerce coordination for paid services. | Good for pay-per-task workflows and settlement. |

Reference links:

- ERC-8004: https://eips.ethereum.org/EIPS/eip-8004
- ERC-8183: https://eips.ethereum.org/EIPS/eip-8183
- x402: https://docs.x402.org/core-concepts/http-402

## Safety Boundary

The profile describes a restricted assistant. It does not include private keys, seed phrases, API keys, tokens, `.env` files, or real-asset account information.
