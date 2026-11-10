# LuxeToken (LUXE) — ERC-20 Token Contract

A clean, self-contained **ERC-20 token** written in Solidity (`^0.8.20`) with no external dependencies — it compiles as-is in Remix or Hardhat.

## Features
- Standard ERC-20: `transfer`, `approve`, `transferFrom`, allowances
- Owner-only `mint` with a hard cap (`MAX_SUPPLY` = 1,000,000 LUXE)
- `burn` — any holder can burn their own tokens
- Ownership transfer with events
- Works on Ethereum, BNB Chain and Polygon (any EVM network)

## Quick start (Remix)
1. Open [remix.ethereum.org](https://remix.ethereum.org) and create `LuxeToken.sol`
2. Compile with Solidity 0.8.20
3. Deploy with an initial supply, e.g. `500000000000000000000000` (500,000 tokens)
4. Interact with the contract from the Deploy panel

## Notes
Portfolio sample contract for demonstration. For production use, get an
independent security review before deploying with real funds.
