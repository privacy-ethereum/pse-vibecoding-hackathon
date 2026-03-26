# PSE Vibecoding Hackathon (Mar 9–10, 2026)

[Privacy & Scaling Explorations (PSE)](https://pse.dev) ran its first vibecoding hackathon — a 2-day, fully remote, mostly async experiment to see what happens when a team of cryptography engineers leans hard into AI-assisted development.

18 people registered. 10 projects were submitted. The range was wild: ZK circuit tooling, post-quantum cryptography, Claude Code plugins for proof generation and circuit auditing, anonymous social networks, and a Tetris-inspired crypto bookkeeping app.

## What's "Vibecoding"?

Vibecoding means building software primarily through AI assistants — Claude, Copilot, Cursor, and similar tools — where the developer focuses on direction, architecture, and iteration while the AI handles much of the code generation. The goal of this hackathon was to explore how well this approach works for serious cryptographic engineering, not just web apps.

## Results

| Place | Project | Team |
|-------|---------|------|
| 1st | **Vibe Circuit** | Sora Suegami, Nam Ngo |
| 2nd | **Seal** | Andrew Morris |
| 3rd | **Noir Circuit Auditor** | Vikas Rushi |

**Honorable Mentions**: Dual Ledger Tower (Nicole Yeh), ShieldETH (Yanis Meziane)

## Submissions

| # | Project | Team | Description | Repo | Demo |
|---|---------|------|-------------|------|------|
| 1 | **Vibe Circuit** | Sora Suegami, Nam Ngo | Claude Code plugin for structured circuit and proof workflows — vibe-code ZK circuits and generate Lean proofs for programmable cryptography | [GitHub](https://github.com/SoraSuegami/vibe-circuit) | [Slides](https://docs.google.com/presentation/d/1a3iog_WDDiPH1gxT1Up_5dTiz9aMO0KehtldY5OxJfw/edit?usp=sharing) |
| 2 | **Anonbook** | Moven, Vivi Jeng | Anonymous social space where bots and AI agents hang out with portable reputation, built on UniRep | [GitHub](https://github.com/moven0831/anonbook) | [Video](https://drive.google.com/file/d/1Lml4MYkNQ2E7JyZDdJ834ZvgXbvn7Wc7/view?usp=sharing) |
| 3 | **ShieldETH** | Yanis Meziane | EIP-8141 Frame Transactions in revm with ZK-verified shielded ETH transfers | [GitHub](https://github.com/Meyanis95/shieldeth) | [Live App](https://meyanis95.github.io/shieldeth/) |
| 4 | **Noir Circuit Auditor** | Vikas Rushi | Claude Code plugin that audits Noir circuits using a 6-phase adversarial protocol across 8 bug classes — found 3 real vulnerabilities in 5 repos | [GitHub](https://github.com/0xVikasRushi/noir-claude-auditor) | [Submission](https://gist.github.com/0xVikasRushi/58fd83b32aa6223d041187188d5f8b13) |
| 5 | **Dual Ledger Tower** | Nicole Yeh | Playful manual bookkeeping app with Tetris-like block placement for crypto-native users | [GitHub](https://github.com/cc03668/dual-ledger-tower) | — |
| 6 | **Seal** | Andrew Morris | Local daemon that serves verified, content-addressed web app bundles over HTTPS on the `.seal` TLD — protecting users from unverifiable web frontends | [GitHub](https://github.com/voltrevo/seal) | [Video](https://drive.google.com/file/d/1II_BRJEgMWlXWJnarePmH_4AR0qfI1pl/view?usp=drivesdk) |
| 7 | **Spartan-WHIR** | Alex Kuzmin | Spartan proving system built on Plonky3 fields with WHIR as the multilinear PCS backend | [GitHub](https://github.com/alxkzmn/spartan-whir) | — |
| 8 | **SortedIMT** | Vivian Plasencia | Optimized Incremental Merkle Tree with efficient membership and non-membership proofs, plus post-quantum resistance | [GitHub](https://github.com/vplasencia/sorted-imt) | [Docs](https://github.com/vplasencia/sorted-imt/blob/main/browser/sorted-imt/doc.md) |
| 9 | **Private Prediction Market** | John Guilding | MPC-based prediction market with LMSR pricing, threshold-signed oracle updates, and ZK-private claims using Circom | [GitHub](https://github.com/JohnGuilding/private-prediction-market-circom) | — |
| 10 | **PQ Private Transfers** | Nicolas Serrano | Private transfer protocol on Ethereum using post-quantum cryptography, built with autonomous AI coding loops | [GitHub](https://github.com/NicoSerranoP/pq-private-transfer) | [Video](https://drive.google.com/file/d/1BwUiPkOwn5pLpoLQ2dVJDs5ooAYvZ1Cl/view?usp=sharing) |

> John Guilding also explored 3 additional projects: [Private Prediction Market (Noir)](https://github.com/JohnGuilding/private-prediction-market-noir), [Canton on Base](https://github.com/JohnGuilding/canton-eth-base), [Canton on Aztec](https://github.com/JohnGuilding/canton-eth-aztec)

## Recordings

- **Judging session** (Wed Mar 11, 13:00 UTC): [Watch recording](https://drive.google.com/file/d/1WAX9W6bi_1VV5AQD8JxE9X987WqKaJmE/view)

## About PSE

[Privacy & Scaling Explorations](https://pse.dev) is a research and development lab within the Ethereum Foundation, focused on building infrastructure for privacy-preserving technologies — zero-knowledge proofs, multi-party computation, and related cryptographic tools.
