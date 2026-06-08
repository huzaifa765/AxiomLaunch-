# AxiomLaunch — Token Launcher on Base

Deploy your own ERC20 token on Base
in under 5 minutes. No code required.

![Base](https://img.shields.io/badge/Built%20on-Base-0052FF?style=for-the-badge)
![Solidity](https://img.shields.io/badge/Solidity-0.8.20-363636?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

## Overview

AxiomLaunch is a permissionless token 
deployment protocol on Base mainnet.

Anyone can deploy a fully functional 
ERC20 token — with mint, burn, and 
ownership controls — through a simple 
interface. No Remix. No Solidity. 
No technical knowledge required.

---

## How It Works

1. Fill out the token form
2. Set name, symbol, supply and features
3. Pay a small deployment fee
4. Your token is live on Base mainnet
5. Share your token page instantly

---

## Features

- **One-click deployment** — ERC20 token live in minutes
- **Custom supply** — set any total supply
- **Mint control** — enable or disable minting
- **Burn control** — enable or disable burning  
- **Ownership** — full control from day one
- **Renounce option** — make token fully decentralized
- **Token directory** — browse all launched tokens
- **Creator profiles** — view all tokens by address

---

## Contract Details

| Contract | Address | Network |
|----------|---------|---------|
| TokenFactory | `0x1e31c4474b6d1bac355faf25d3b7b11c9d418ad9` | Base Mainnet |
| BaseToken (template) | `0x624fbe6affc10a45974f3b1b551fdb8a1ba0a092` | Base Mainnet |

- Compiler: Solidity 0.8.20
- EVM: London
- Optimization: Enabled — 200 runs
- Both contracts verified on BaseScan

🔗 [TokenFactory on BaseScan](https://basescan.org/address/0x1e31c4474b6d1bac355faf25d3b7b11c9d418ad9)

---

## Core Functions

```solidity
// Launch a new token
launchToken(name, symbol, decimals, supply, mintable, burnable)

// Get token info
getToken(tokenId)

// Get all tokens by creator
getCreatorTokens(address)

// Get latest launches
getLatestTokens()
```

---

## Tech Stack

- Solidity 0.8.20
- Base Mainnet
- Ethers.js v6
- Vanilla JavaScript
- Deployed on Vercel

---

## Roadmap

- [x] ERC20 token factory contract
- [x] BaseToken template with mint/burn
- [x] Both contracts verified on BaseScan
- [ ] Frontend launcher UI
- [ ] Token directory page
- [ ] Individual token pages
- [ ] Uniswap liquidity integration

---

## Builder

[@Huzaifa_0101](https://twitter.com/Huzaifa_0101)
on Base since February 2024

---

## License

MIT
