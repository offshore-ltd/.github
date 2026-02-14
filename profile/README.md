<div align="center">

# 🌊 Offshore Cash

### Privacy-preserving transfers on Ethereum

[![Website](https://img.shields.io/badge/offshore.ltd-000000?style=for-the-badge&logo=google-chrome&logoColor=94febf)](https://offshore.ltd)
[![Docs](https://img.shields.io/badge/Documentation-000000?style=for-the-badge&logo=gitbook&logoColor=94febf)](https://docs.offshore.ltd)
[![App](https://img.shields.io/badge/Launch_App-000000?style=for-the-badge&logo=ethereum&logoColor=94febf)](https://app.offshore.ltd)

---

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=3000&pause=1000&color=94FEBF&center=true&vCenter=true&repeat=true&width=500&lines=Zero-knowledge+proofs+%E2%80%A2+Groth16;Arbitrary+deposit+amounts;Partial+withdrawals+with+change;Decentralized+relayer+network;Revenue+share+staking;On-chain+governance" alt="Features" />

</div>

---

## How It Works

```
Deposit ETH → ZK Proof → Withdraw to any address
```

Offshore Cash breaks the on-chain link between sender and receiver using **ZK-SNARKs**. Deposits go into a shared pool. Withdrawals are processed through relayers — no one can trace which deposit belongs to which withdrawal.

## Protocol

| | |
|---|---|
| **Network** | Ethereum |
| **Proof System** | Groth16 (snarkjs + circom) |
| **Hash Function** | Poseidon |
| **Merkle Tree** | Depth 20 (~1M deposits) |
| **Token** | OFF (100M fixed supply) |
| **Fee Model** | Relayer keeps ETH fee · Protocol charges 0.3% in OFF → stakers |
| **Governance** | On-chain proposals · 2-day timelock · 50K OFF threshold |

## Repositories

| Repo | Description |
|:-----|:------------|
| [`contracts`](https://github.com/offshorecash/contracts) | Solidity smart contracts, ZK circuits, deploy scripts, tests |
| [`app`](https://github.com/offshorecash/app) | Frontend application (Next.js) |
| [`sdk`](https://github.com/offshorecash/sdk) | TypeScript SDK — Poseidon, Merkle tree, proof generation |
| [`relayer`](https://github.com/offshorecash/relayer) | Relay service (Bull + Redis, multi-worker) |
| [`docs`](https://github.com/offshorecash/docs) | Protocol documentation (VitePress) |

## Tech Stack

<div align="center">

![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Circom](https://img.shields.io/badge/Circom-4A90D9?style=flat-square&logo=data:image/svg+xml;base64,&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=flat-square&logo=ethereum&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

</div>

## Tokenomics

```
████████████████████████████████████████████████████████████████░ 65%  Treasury (5yr vesting)
████████████████████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ 25%  Team (3yr vesting)
████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░  5%  Base Relayer
████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░  5%  Liquidity (LP burned)
```

---

<div align="center">

**Your funds. Your privacy.**

<sub>Built on Ethereum · Secured by zero-knowledge proofs</sub>

</div>
