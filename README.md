# DynaRealm

**A gamified SocialFi and DeFi metaverse built on NERO Chain, empowering creators, players, and communities through seamless Web3 onboarding and gasless transactions.**

---

## Table of Contents

- [Overview](#overview)
- [Why DynaRealm](#why-dynarealm)
- [Key Features](#key-features)
- [How It Uses NERO Chain](#how-it-uses-nero-chain)
- [Tech Stack](#tech-stack)
- [User Flow](#user-flow)
- [Paymaster Integration](#paymaster-integration)

---

## Overview

**DynaRealm** is an all-in-one metaverse platform blending **GameFi**, **SocialFi**, and **DeFi**, designed to make Web3 accessible and fun for the next billion users. Built on **NERO Chain**, it leverages the **Paymaster (AA-platform)** to eliminate onboarding friction, support gasless transactions, and allow anyone to participate—even without prior crypto knowledge.

---

## Why DynaRealm

- Mass adoption of Web3 is limited by friction in UX and on-chain interaction.
- Most platforms focus on one vertical: gaming, finance, or social.
- DynaRealm offers a unified experience where:
  - Players **earn** from gameplay (GameFi).
  - Users **connect** and collaborate (SocialFi).
  - Participants **invest** in creators and assets (DeFi).

---

## Key Features

### GameFi
- Participate in on-chain quests and real-time multiplayer games.
- Earn $REALM tokens and NFT rewards.
- Guild system with dynamic in-game governance.

### SocialFi
- Profiles, follower economy, and fan tokens.
- Content monetization through streaming, writing, and digital assets.
- Reputation-based ranking with on-chain proofs.

### DeFi
- Stake your $REALM or NFTs to earn yield or power-ups.
- Tokenized in-game assets with liquidity pools.
- Creator Vaults for crowdfunding and revenue sharing.

### NERO Paymaster Integration
- Gasless onboarding using email/social logins.
- Use any token as gas (configurable by dApp).
- Transaction sponsorship for new users and community campaigns.

---

## How It Uses NERO Chain

| NERO Feature           | How DynaRealm Uses It                                               |
|------------------------|---------------------------------------------------------------------|
| **Paymaster (AA)**     | Gasless transactions, account abstraction, token-as-gas             |
| **Blockspace 2.0**     | Reduced MEV for fair gameplay and secure financial interaction      |
| **Token Utility**      | All tokens used across gameplay, social rewards, and DeFi features  |
| **Seamless UX**        | Instant wallet creation, frictionless login, and intuitive Web2-like UI |

---

## Tech Stack

- **Smart Contracts**: Solidity on NERO Chain (EVM-compatible)
- **Frontend**: React, TypeScript, Tailwind CSS
- **Backend**: Node.js, MongoDB
- **Authentication**: Web3Modal + Social Login (via NERO integration)
- **Paymaster**: Integrated via [NERO AA SDK](https://docs.nerochain.io/en/tutorials)

---

## User Flow

1. **User visits DynaRealm**
   - No wallet needed
   - Login with Google or Twitter
2. **Instant wallet creation (via AA)**
3. **User chooses role**: Player / Creator / Investor
4. **Explore Realms** (mini-metaverses)
   - Play, earn, socialize, and invest
5. **Gasless actions using Paymaster**
6. **Track progress and assets from dashboard**

---

## Paymaster Integration

- **Sponsorship Setup**:
  - New users get 10 free transactions sponsored by DynaRealm.
  - Paymaster is configured to support $REALM or any major ERC-20 token on NERO.
- **Account Abstraction**:
  - User wallet is abstracted from day one.
  - Single-click login, no Metamask popups or manual signing required.
- **Custom Gas Logic**:
  - Users can pay gas using game rewards or social tokens.
  - Creators can sponsor fans’ gas fees for engagement boosts.
