# Week 1 Minimal Smart Contract Record

## Goal

Deploy or call one minimal smart contract on a testnet and record public verification information.

## Contract

- Contract file: `experiments/MinimalStorage.sol`
- Tool: Remix
- Network: Sepolia Testnet
- Wallet: test-only wallet

## Contract Summary

`MinimalStorage` stores one `uint256` value.

- `constructor(uint256 initialValue)`: sets the initial value during deployment.
- `setValue(uint256 newValue)`: writes a new value to chain and emits `ValueChanged`.
- `getValue()`: reads the current value without sending a transaction.

## Deployment Record

- Contract address: `0x6eb139c4E31457Ce033BAcb2bfC95AdF6deF7E5A`
- Deployment transaction hash: `0xda61cdc0663391f11b3b2eb748fc7866ed77dc441dc706e4bd828eefb96b3079`
- Deployment explorer link: https://sepolia.etherscan.io/tx/0xda61cdc0663391f11b3b2eb748fc7866ed77dc441dc706e4bd828eefb96b3079
- Deployment status: Success
- Block number: `10947601`
- Initial value: `42`
- Verification notes:
  - Sourcify verification: https://repo.sourcify.dev/11155111/0x6eb139c4E31457Ce033BAcb2bfC95AdF6deF7E5A/
  - Blockscout verification: https://eth-sepolia.blockscout.com/address/0x6eb139c4E31457Ce033BAcb2bfC95AdF6deF7E5A?tab=contract
  - Etherscan source verification was skipped because no Etherscan API key was configured in Remix.

## Interaction Record

- Read function called: `getValue()`
- Initial read result: `42`
- Write function called: `setValue(uint256 newValue)`
- New value: `100`
- Write transaction hash: `0xbbb96b4203015b7b858846432b3790a48431b6621e77194e2b71a369ad868e3f`
- Write explorer link: https://sepolia.etherscan.io/tx/0xbbb96b4203015b7b858846432b3790a48431b6621e77194e2b71a369ad868e3f
- Write status: Success
- Block number: `10947615`
- Transaction input note: calldata ended with `00064`, which is hexadecimal for `100`.
- Event log: `ValueChanged(100)` emitted, shown by Remix as `logs: 1`.
- Gas used: recorded on the block explorer transaction page.

## Human Confirmation Record

- Codex prepared the Remix contract file, deployment parameters, and interaction parameters.
- I manually confirmed the deployment transaction in MetaMask.
- I manually confirmed the `setValue(100)` transaction in MetaMask.
- I checked that this was on Sepolia testnet and did not use a real-asset wallet.

## What I Learned

- Deployment is a transaction because it writes contract code and initial state to the network.
- Reading a `view` function does not require gas or a wallet transaction.
- Writing to a contract changes on-chain state and requires wallet confirmation.
- The contract address and transaction hashes are the public proof.

## Safety Notes

- Use Sepolia testnet only.
- Use a test-only wallet.
- Do not include private keys, seed phrases, API keys, tokens, `.env` files, or real asset information.
