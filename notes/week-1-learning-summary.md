# Week 1 AI x Web3 Learning Summary

## Overview

Week 1 helped me build a basic AI x Web3 learning loop: use an AI agent to help plan, draft, explain, and organize; use GitHub to keep a public learning trail; use testnet actions and block explorers to verify Web3 practice. My biggest takeaway is that AI is very useful for learning acceleration, but Web3 execution still needs strict human confirmation.

Repository:

https://github.com/Connor532/ai-web3-school-cohort-0

## One AI Concept I Re-understood: Agent And Tool Use

Before Week 1, I mostly thought of AI as a chat tool that answers questions. After using Codex as a Learning Agent, I started to understand an agent as a workflow participant that can read files, create notes, organize tasks, operate tools, and maintain a learning repo.

The important difference is that an agent is not just "smarter text generation." It becomes useful when it can connect reasoning with tools, but that also means it needs clear boundaries. In my Week 1 work, the agent could draft learning plans, write Markdown notes, prepare contract records, and explain wallet prompts, but it could not hold private keys, sign wallet messages, or confirm transactions.

## One Web3 Concept I Re-understood: Wallets, Signatures, And Transactions

I used to think of a wallet mostly as a login account. Week 1 made this feel too simple. A wallet controls an address through private key material, and a signature or transaction can authorize real actions.

A transaction is not only a "send money" action. It can also deploy a contract or call a write function on a contract. Gas is the cost of asking the network to execute and record the action. A block explorer then becomes the public verification layer: I can use a transaction hash, contract address, block number, and status to prove what happened.

## AI x Web3 Cross-over Question

The key question I kept returning to was:

> Can an AI agent help with Web3 actions without becoming unsafe?

My current answer is: yes, but only if the agent is limited to preparation, explanation, checking, and documentation. The human must still confirm wallet creation, network changes, message signatures, token approvals, transactions, contract deployments, and contract write calls. A safe pattern for me is:

```text
AI drafts -> human reviews -> wallet confirms -> testnet executes -> explorer verifies -> GitHub records
```

This pattern keeps AI helpful while keeping authority and responsibility with the human.

## Proof-of-Work Completed

Main repo:

https://github.com/Connor532/ai-web3-school-cohort-0

Selected Week 1 outputs:

- Learning Agent setup: https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/tasks/week-1-learning-agent-setup.md
- AI concept cards: https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/notes/ai-concepts-week-1.md
- Web3 concept cards: https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/notes/web3-concepts-week-1.md
- EOA / smart account / multisig comparison: https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/notes/eoa-smart-account-multisig.md
- AI x Web3 minimal flow: https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/experiments/ai-web3-minimal-flow.md
- Restricted Web3 assistant workflow: https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/experiments/restricted-web3-assistant-workflow.md
- Interactive quiz demo: https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/demos/week-1-concept-quiz.html
- Industry follow list: https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/resources/follow-list-week-1.md
- Week 1 Proof-of-Work pack: https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/tasks/week-1-pow-pack.md

On-chain practice:

- Sepolia testnet transaction: https://sepolia.etherscan.io/tx/0xda40ac15168492e0dbde83806cfd2f53df456155d27fa74d92db917f9c693555
- MinimalStorage contract address: `0x6eb139c4E31457Ce033BAcb2bfC95AdF6deF7E5A`
- Contract deployment transaction: https://sepolia.etherscan.io/tx/0xda61cdc0663391f11b3b2eb748fc7866ed77dc441dc706e4bd828eefb96b3079
- Contract write call `setValue(100)`: https://sepolia.etherscan.io/tx/0xbbb96b4203015b7b858846432b3790a48431b6621e77194e2b71a369ad868e3f

## What I Learned From The Smart Contract Task

The `MinimalStorage` contract stores one `uint256` value. I deployed it with initial value `42`, then called `setValue(100)` on Sepolia.

This helped me understand the difference between:

- Deploying a contract: writing contract code and initial state to the network.
- Reading a contract: calling a `view` function without sending a transaction.
- Writing to a contract: changing on-chain state through a wallet-confirmed transaction.

It also made the verification loop concrete: contract address, transaction hash, block explorer status, and GitHub notes together form the proof.

## One Thing I Still Have Not Solved

I still do not fully understand how to safely grant limited permissions to AI agents through smart accounts or session keys. The idea sounds useful, but the hard part is designing limits that are clear, revocable, auditable, and hard to misuse.

For Week 2, I want to keep exploring:

- Account abstraction and smart account permissions.
- How AI agents should explain wallet prompts.
- How to evaluate whether an agent's Web3 recommendation is correct.
- How to move from Remix experiments to a local contract development workflow with tests.

## Safety Notes

This summary does not include private keys, seed phrases, API keys, tokens, `.env` files, private course links, or real-asset sensitive information. All wallet actions were done on Sepolia testnet with human confirmation.
