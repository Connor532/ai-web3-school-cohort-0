# Week 1 Web3 Concept Cards

## Account

An account is an entity that can own assets and initiate or receive on-chain actions. In Ethereum-style systems, common account types include externally owned accounts and smart contract accounts.

## Address

An address is a public identifier derived from an account. It can receive assets and appear in block explorers.

Privacy note: addresses are public and can often be linked through transaction history.

## Wallet

A wallet is the user-facing tool that manages keys and helps create signatures or transactions. It is not the same thing as a Web2 username/password account.

Safety rule: use a test-only wallet for course experiments.

## Seed Phrase

A seed phrase can recover a wallet. Anyone who has it can control the wallet.

Public repo rule: never commit or screenshot a seed phrase.

## Private Key

A private key authorizes control over an account. It must remain secret.

AI safety rule: an AI agent should never receive a private key.

## Signature

A signature proves that a wallet approved a specific message or transaction. Signing is not "just logging in"; it can authorize meaningful actions.

Human-in-the-loop rule: review the message before signing.

## Transaction

A transaction changes on-chain state, such as transferring test ETH, calling a contract, or deploying a contract.

Proof record: transaction hash, status, gas, block number, and explorer link.

## Gas

Gas is the execution resource cost for blockchain operations. Even failed transactions may consume gas.

Week 1 rule: practice on testnets first.

## Smart Contract

A smart contract is on-chain code with public state and executable functions. It can be read, called, and inspected through tools like Remix and block explorers.

## Block Explorer

A block explorer lets users inspect addresses, transactions, blocks, contracts, and events.

Week 1 use: verify test transactions and contract deployments.

## EOA, Smart Account, Multisig

- EOA: controlled directly by a private key.
- Smart account: controlled by contract logic and can support richer permissions.
- Multisig: requires multiple approvals before execution.

AI x Web3 relevance: agent workflows need permission limits, spending caps, revocation, logs, and human approval for risky actions.

