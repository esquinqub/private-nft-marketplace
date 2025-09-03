# Private NFT Marketplace — Confidential Bids & Purchases with FHEVM

A privacy-preserving NFT marketplace built with Zama’s FHEVM.  
Sellers list NFTs with encrypted prices. Buyers place encrypted bids.  
Sales resolve with fail-closed logic: if bid < price, transaction resolves to 0 without revealing values.

## ✨ Features
- Encrypted listing prices (`euint64`)
- Confidential bids
- Fail-closed acceptance
- NFT transfers only when conditions are met
- Fully EVM-compatible

## ⚙ Quickstart
```bash
npm i
npx hardhat test
