# Complect ⛙

[![Follow on X](https://img.shields.io/badge/Follow%20on%20X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/complectlabs)

**The infrastructure that ends the fake growth era in Web3.**

Complect is the first Web3 growth infrastructure that dynamically routes cryptographic verification based on financial task value, guaranteeing retention and eliminating Sybil attacks without compromising user privacy

## The Problem: Web3 Growth is a Lie
Projects spend millions on marketing, airdrops, and quests only for **bot farms** and fake accounts to take most of the rewards.

Result?
- Fake metrics that look good on paper
- Almost zero real user retention after the incentives end
- Communities that disappear when the airdrop is over
- Billions wasted every year on growth that isn't real


The cause is simple: The blockchain verifies that a transaction happened, but it does not verify that a human decided to make it. Current tools use the same weak friction (like a CAPTCHA) whether the reward is $1 or $10,000. Bots bypass it easily while real humans suffer the friction.

## The Solution

**Complect** is an infrastructure that makes **real human participation** the only profitable way to grow in Web3. We believe that verification friction should be directly proportional to the financial value of the task (adjustable to match each advertisable preferences). Complect ingests campaign parameters and automatically routes users through the precise level of Zero-Knowledge (ZK) verification required to eliminate bots, while maximizing human conversion rates.


## How Complect Works 

Think of Complect as a trusted referee for Web3 growth campaigns:

1. **Protocols & Advertisers** create a campaign on Complect. They define what they want (ranked game quest, game assets unlock, more liquidity, governance votes, user onboarding, brand awareness, presales, meme campaigns, airdrops, etc.) and how much they’re willing to pay for real results.
<p align="center">
  <img width="1723" height="1112" alt="Screenshot 2026-05-29 at 05 30 05" src="https://github.com/user-attachments/assets/3bd726b7-7474-49b2-a8a5-57e728794705" />
</p>
2. **Publishers** (wallets, dApps, explorers, media sites, and content creators) promote the campaign. They embed a simple widget on their platform and earn up to **25% revenue share** every time a verified user completes a task through their channel. No extra work needed, they just monetize their existing audience.

3. **Users & Explorers** discover and complete meaningful tasks. They see high-quality opportunities in the personalized discovery feed, complete real actions (swaps, staking, reaching levels in games, minting NFTs, creating content, ranked matches, etc.) across Avalanche and other EVM chains, and build a portable reputation passport that follows.

4. **Complect verifies on-chain** that it was a real human (not a bot). Using adaptive verification (light checks for small tasks, stronger proof for high-value ones).

5. **Rewards are paid automatically and trustlessly** Only after successful verification. Rewards can be in any form the campaign supports (tokens, NFTs, points, etc.).

<p align="center">
  <img src="https://github.com/user-attachments/assets/e7507f00-9974-4c7f-9ecb-1e98c8e3899f" alt="Complect Ecosystem GIF" />
</p>

## Key Features

- **Sybil-Resistant Verification** — On-chain proof that a real human performed the action (powered by Medulla: proprietary software)
- **Reputation Passport** — Portable score based on real activity across chains
- **Trustless Reward Vaults** — Rewards released automatically only after verification
- **Publisher Widgets** — Easy embed for wallets and dApps (monetization without friction)
- **Discovery Feed** — Personalized, high-signal quests and opportunities
  <p align="center">
    <img width="1522" height="1000" alt="Screenshot 2026-07-02 at 02 38 13" src="https://github.com/user-attachments/assets/e50e86a5-3b11-4ba9-8c1f-979b78c7b78b" />
  </p>
- **Cross-Chain Ready** — Works across Avalanche and other EVM chains via Teleporter
- **High Performance** — Built for Avalanche speed and low cost
  
---

## Complect Verification Framework
Complect’s verification system adapts to the value of each task. Advertisers can set the strictness of checks, ensuring that low‑value actions remain frictionless while high‑value rewards could require stronger proof. 

| Task Value | Verification Level    | Technology Used          | Why We Chose It                                                                                                                                                          |
| ---------- | --------------------- | ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Low        | Social Graph          | Gitcoin Passport         | Zero friction for users. Instantly filters out low-effort bots using existing Web2/Web3 reputation signals without requiring KYC or additional apps.                     |
| Medium     | Hardware Attestation  | Holonym (Proof of Phone) | Makes Sybil attacks significantly more expensive by requiring proof of control over a physical SIM/device, bridging the gap between social reputation and government ID. |
| High       | Sovereign ZK Identity | Self Protocol            | Provides the strongest guarantee of unique human verification through zero-knowledge proofs while preserving privacy—no personal data leaves the user's device.          |



## Future Integration: Proof of Cognitive Echo (PoCE)
While ZK-Identity solves the problem of uniqueness, it does not solve the problem of engagement quality. Complect is developing a passive layer that measures natural human behavior (like how your eyes and hands interact with the screen) to further improve quality scoring without adding friction.

### The Concept:
AI can solve a logic puzzle instantly. A robot arm can perfectly move a mouse. But AI cannot simulate the exact, messy, millisecond-level biological delay and physical micro-tremors of a human eye and hand working together to comprehend a sensory puzzle.

### How PoCE Works:
PoCE relies on Neuromorphic Micro-Interactions and Dynamic Micro-Challenges. Instead of asking "Are you human?" (like a CAPTCHA), PoCE measures the microscopic, involuntary physical responses (echoes) that occur when a human brain processes a sensory puzzle, such as an optical illusion, a visual joke, or a physical balance game.

- **What it measures**: Eye-tracking micro-saccades, mouse trajectory entropy, and cognitive processing delay.

- **The Goal**: PoCE will act as a passive, zero-friction layer running in the background of the Complect Explorer. It will not block users; rather, it will generate a _Cognitive Trust Score_ for every wallet, allowing advertisers to dynamically adjust payout multipliers based on the biological humanity of the user's interaction.

