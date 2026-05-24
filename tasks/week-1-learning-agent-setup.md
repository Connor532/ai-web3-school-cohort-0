# Week 1 Learning Agent Setup Record

## 1. Selected Agent / AI Tool

Primary tool: Codex

Role: AI x Web3 School Learning Agent

Why I chose it:

- It can read and edit my local learning repository.
- It can help turn course tasks into Markdown notes, checklists, templates, and proof-of-work records.
- It can keep the learning process organized across README, daily notes, task notes, experiments, and submissions.

Optional tools considered:

- Claude Code: useful for code review or comparison later.
- Cursor: useful if Week 1 experiments become code-heavy.
- GLM API / Z.ai / Hermes Agent: optional paths for later model or agent workflow comparison.

## 2. Learning Tasks I Asked The Agent To Help With

I asked Codex to help with these Week 1 learning tasks:

- Read the official Learning Agent startup prompt and Handbook overview.
- Initialize my AI x Web3 School GitHub learning repository.
- Draft `README.md`, `learning-plan.md`, `profile.md`, daily notes, task notes, and templates.
- Prepare a Week 1 tool setup record.
- Create AI concept cards and Web3 concept cards.
- Create a minimal AI x Web3 workflow diagram.
- Create a small interactive concept quiz demo.
- Organize Week 1 proof-of-work links for task submission.
- Help write daily check-in drafts.

## 3. Key Prompt / Configuration Note

Key prompt used:

```text
请作为我的 AI × Web3 School Learning Agent，先阅读启动 Prompt：https://aiweb3.school/learning-agent.zh.txt ，并结合 Handbook：https://aiweb3.school/zh/handbook/ ，帮我初始化个人学习计划、GitHub 学习仓库、每日打卡草稿和 Handbook feedback 流程。
```

Working configuration:

- Repository: `ai-web3-school-cohort-0`
- Visibility: public
- Main purpose: personal learning log, task proof, experiments, daily check-in drafts, Handbook feedback, and Hackathon preparation
- Safety rule: do not commit API keys, private keys, seed phrases, tokens, `.env` files, private links, or other sensitive information
- Human confirmation required for: GitHub repo creation, commits, pushes, public submissions, wallet signatures, testnet transactions, and contract writes

## 4. Successful Output Record

Codex successfully generated the initial learning repository structure and learning materials.

Output examples:

- Main repo: https://github.com/Connor532/ai-web3-school-cohort-0
- README: https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/README.md
- Learning plan: https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/learning-plan.md
- Daily note: https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/daily/2026-05-23.md
- Week 1 tool preparation: https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/tasks/week-1-tools.md
- AI concept cards: https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/notes/ai-concepts-week-1.md
- Week 1 Proof-of-Work Pack: https://github.com/Connor532/ai-web3-school-cohort-0/blob/main/tasks/week-1-pow-pack.md

One successful output I used:

```text
今天完成了 AI x Web3 School 个人学习仓库初始化。我使用 Learning Agent 阅读了官方启动 Prompt 和 Handbook 概览，建立了 README、学习计划、每日记录、任务记录、实验记录、Handbook feedback 和 Hackathon 准备目录。Week 1 的目标是熟悉 Handbook 知识地图，建立每日打卡节奏，并产出至少一个任务记录、实验记录或 Handbook feedback。
```

## 5. Human Review, Correction, Or Rejection Record

I did not accept every Agent action automatically.

Human review and corrections:

- I manually completed GitHub CLI login because account authentication requires human control.
- I manually confirmed Xcode license and GitHub repo creation steps in Terminal.
- I manually ran commit and push commands when the Agent environment could not write Git metadata.
- I checked generated Markdown before using it as public proof-of-work.
- I asked the Agent to expand the AI concept cards because the first version was too short for the task requirements.

Rejected or delayed Agent actions:

- I did not let the Agent create or use a wallet.
- I did not let the Agent sign messages, send transactions, or deploy contracts.
- I did not put API keys, private keys, seed phrases, tokens, `.env` files, or private course links into the repository.

Reason:

The Agent is useful for planning, drafting, organizing, and checking, but actions involving accounts, public submission, wallets, signatures, and on-chain execution need human confirmation.

## 6. Safety And Privacy Check

This record is safe for public submission.

It does not include:

- API keys
- Tokens
- Private keys
- Seed phrases
- `.env` files
- Passwords
- Private meeting links
- Non-public course links

