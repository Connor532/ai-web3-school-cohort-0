# Week 1 AI Concept Cards

## LLM

A Large Language Model generates text by predicting likely token sequences from the context it can see. It is useful for explanation, summarization, code drafting, and reasoning support, but its outputs still need verification.

Risk note: an LLM can sound confident while producing incorrect facts, broken links, or unsafe instructions.

## Prompt

A prompt is the current instruction or task given to the model. It should include context, goal, constraints, expected output format, and safety boundaries.

Week 1 use: ask the Learning Agent to turn course requirements into a checklist, learning plan, and repo artifacts.

## Context Window

The context window is the model's working memory for a single interaction. It can include system instructions, user instructions, prior messages, files, and tool results.

Practical rule: keep important facts explicit in the current task instead of assuming the model remembers everything.

## Workflow

A workflow is a predefined process where AI may help at one or more steps, but the path is mostly fixed.

Example: read course task, draft note, human review, commit to GitHub, submit proof link.

## Agent

An agent can plan steps, call tools, read files, write files, and continue across a multi-step task. It is more powerful than a one-shot prompt, but also needs clearer boundaries.

Week 1 boundary: the agent can draft repo files and submission text, but the human confirms GitHub commits, wallet actions, signatures, and submissions.

## Tool Use

Tool use lets an AI system move from "answering" to "doing": reading pages, editing files, running commands, creating diagrams, or using APIs.

Safety rule: tool access should be scoped, observable, and reversible when possible.

## AI Coding

AI coding tools such as Codex, Claude Code, and Cursor can generate code, inspect repos, explain errors, and maintain learning artifacts.

Human role: review code, check links, test outputs, and decide whether changes should be committed.

## Verification

Verification means checking AI output against sources, tests, screenshots, logs, or public records.

Week 1 proof examples:

- GitHub commit history
- Markdown notes
- Browser-openable demo
- Block explorer transaction links
- Screenshots without secrets

