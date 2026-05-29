# Week 1 Proof-of-Work Pack

## Repository

- Repo: https://github.com/Connor532/ai-web3-school-cohort-0
- Purpose: AI x Web3 School learning logs, tasks, experiments, feedback, and Hackathon preparation.

## Completed Proof Items

| Task Area | Evidence |
| --- | --- |
| Learning Agent setup | https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/tasks/week-1-learning-agent-setup.md |
| GitHub learning repo | https://github.com/Connor532/ai-web3-school-cohort-0 |
| Tool preparation | https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/tasks/week-1-tools.md |
| AI concept cards | https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/notes/ai-concepts-week-1.md |
| Web3 concept cards | https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/notes/web3-concepts-week-1.md |
| EOA / smart account / multisig comparison | https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/notes/eoa-smart-account-multisig.md |
| AI x Web3 minimal flow | https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/experiments/ai-web3-minimal-flow.md |
| Restricted Web3 assistant workflow | https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/experiments/restricted-web3-assistant-workflow.md |
| Interactive learning artifact | https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/demos/week-1-concept-quiz.html |
| Industry follow list | https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/resources/follow-list-week-1.md |
| Industry observation | https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/resources/industry-observation-week-1.md |
| Week 1 learning summary | https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/notes/week-1-learning-summary.md |
| Testnet transaction | https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/tasks/week-1-testnet-transaction.md |
| Minimal smart contract deployment/call | https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/tasks/week-1-minimal-contract.md |
| Minimal smart contract code | https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/experiments/MinimalStorage.sol |
| Submission guide | https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/submissions/week-1-task-submit-guide.md |

## Learning Agent Log

Codex helped:

- Read the official Learning Agent startup prompt and Handbook.
- Create the initial repository structure.
- Draft Week 1 goals and daily notes.
- Prepare AI and Web3 concept cards.
- Produce a minimal AI x Web3 workflow diagram.
- Build a small browser-openable quiz demo.
- Draft remaining Week 1 written submissions.
- Prepare copy-ready submission descriptions.
- Maintain a privacy-first checklist.

Human confirmed:

- GitHub CLI login.
- Repository creation.
- Commits and pushes.
- Any action involving public submission.
- Wallet connection, testnet transaction, contract deployment, and contract write call in MetaMask.

## Problem / Blocker / Human Correction Record

- Blocker: `brew` and `gh` were not available at first, so GitHub CLI installation and login had to be fixed before creating and pushing the repo.
- Blocker: GitHub CLI downloaded as a zip file did not work until the executable was correctly placed and called from terminal.
- Human confirmation: Xcode license acceptance, GitHub authentication, repo creation, commits, and pushes were confirmed manually.
- Human correction: AI/Codex could prepare Remix code and parameters, but wallet confirmations were kept manual. The human confirmed the Sepolia test transaction, contract deployment, and `setValue(100)` call in MetaMask.
- Learning correction: I initially treated wallet tasks like normal software setup, but Week 1 made it clear that signatures, approvals, and transactions need a separate safety checklist.

## On-chain Proof

- Testnet transfer transaction: https://sepolia.etherscan.io/tx/0xda40ac15168492e0dbde83806cfd2f53df456155d27fa74d92db917f9c693555
- MinimalStorage contract address: `0x6eb139c4E31457Ce033BAcb2bfC95AdF6deF7E5A`
- Contract deployment transaction: https://sepolia.etherscan.io/tx/0xda61cdc0663391f11b3b2eb748fc7866ed77dc441dc706e4bd828eefb96b3079
- Contract write call `setValue(100)`: https://sepolia.etherscan.io/tx/0xbbb96b4203015b7b858846432b3790a48431b6621e77194e2b71a369ad868e3f

## Minimal Smart Contract Proof

- Contract: `MinimalStorage`
- Network: Sepolia Testnet
- Contract address: `0x6eb139c4E31457Ce033BAcb2bfC95AdF6deF7E5A`
- Deployment transaction: https://sepolia.etherscan.io/tx/0xda61cdc0663391f11b3b2eb748fc7866ed77dc441dc706e4bd828eefb96b3079
- Contract call transaction: https://sepolia.etherscan.io/tx/0xbbb96b4203015b7b858846432b3790a48431b6621e77194e2b71a369ad868e3f
- Manual confirmation: deployment and `setValue(100)` were both confirmed by me in MetaMask.

## Safety Boundary

This pack does not include API keys, private keys, seed phrases, tokens, `.env` files, private course links, or non-public meeting links.
