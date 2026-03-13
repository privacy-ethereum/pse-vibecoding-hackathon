# PSE Vibecoding Hackathon (Mar 9–10, 2026)

PSE's first internal vibecoding hackathon — a 2-day, fully remote, mostly async experiment to see what our team can build when leaning hard on AI-assisted development. 18 people registered, 10 projects were submitted, ranging from ZK circuit tooling and post-quantum cryptography to playful crypto bookkeeping apps.

The premise was simple: pick a problem, use whatever AI tools you want (Claude, Copilot, Cursor, etc.), and ship something in two days. Teams of up to 3, solo welcome. No restrictions on what to build — internal tooling, dogfooding PSE tech, or something completely unhinged.

Coordination happened in Mattermost, with two optional live training sessions on vibecoding (led by Moven and Sora) in the week before, and a live judging session at the end.

## Recordings

- **Judging session** (Wed Mar 11, 13:00 UTC): [Watch recording](https://drive.google.com/file/d/1WAX9W6bi_1VV5AQD8JxE9X987WqKaJmE/view)

## Submissions

| # | Project | Team | Description | Repo | Demo |
|---|---------|------|-------------|------|------|
| 1 | **Vibe Circuit** | Sora Suegami, Nam Ngo | Claude Code plugin for vibe-coding ZK circuits and generating Lean proofs for programmable cryptography | [GitHub](https://github.com/SoraSuegami/vibe-circuit) | [Slides](https://docs.google.com/presentation/d/1a3iog_WDDiPH1gxT1Up_5dTiz9aMO0KehtIdY5OxJfw/edit?usp=sharing) |
| 2 | **Anonbook** | Moven, Vivi Jeng | Anonymous social space where bots and AI agents hang out with portable reputation, built on UniRep | [GitHub](https://github.com/moven0831/anonbook) | [Video](https://docs.google.com/presentation/d/1a3iog_WDDiPH1gxT1Up_5dTiz9aMO0KehtldY5OxJfw/edit?slide=id.p1#slide=id.p1) |
| 3 | **ShieldETH** | Yanis Meziane | EIP-8141 Frame Transactions in revm with ZK-verified shielded ETH transfers | [GitHub](https://github.com/Meyanis95/shieldeth) | [Live App](https://meyanis95.github.io/shieldeth/) |
| 4 | **Noir Circuit Auditor** | Vikas Rushi | Claude Code plugin that audits Noir circuits using a 6-phase adversarial protocol, covering 8 bug classes. Found 3 real vulnerabilities across 5 repos. | [GitHub](https://github.com/0xVikasRushi/noir-claude-auditor) | [Submission](https://gist.github.com/0xVikasRushi/58fd83b32aa6223d041187188d5f8b13) |
| 5 | **Dual Ledger Tower** | Nicole Yeh | Playful manual bookkeeping app with Tetris-like block placement for crypto-native users | [GitHub](https://github.com/cc03668/dual-ledger-tower) | — |
| 6 | **Seal** | Andrew Morris | Local daemon that serves verified, content-addressed web app bundles over HTTPS — protecting users from unverifiable web frontends | [GitHub](https://github.com/voltrevo/seal) | [Video](https://drive.google.com/file/d/1Il_BRJEgMWIXWJnarePmH_4AR0qfl1pl/view?usp=drivesdk) |
| 7 | **Spartan-WHIR** | Alex Kuzmin | Spartan proving system built on Plonky3 fields with WHIR as the multilinear PCS backend | [GitHub](https://github.com/alxkzmn/spartan-whir) | — |
| 8 | **SortedIMT** | Vivian Plasencia | Optimized Incremental Merkle Tree supporting efficient membership and non-membership proofs with post-quantum resistance | [GitHub](https://github.com/vplasencia/sorted-imt) | [Docs](https://github.com/vplasencia/sorted-imt/blob/main/browser/sorted-imt/doc.md) |
| 9 | **Private Prediction Market** | John Guilding | MPC-based prediction market with LMSR pricing, threshold-signed oracle updates, and ZK-private claims using Circom | [GitHub](https://github.com/JohnGuilding/private-prediction-market-circom) | — |
| 10 | **PQ Private Transfers** | Nicolas Serrano | Private transfer protocol on Ethereum using post-quantum cryptography, built with autonomous AI coding loops | [GitHub](https://github.com/NicoSerranoP/pq-private-transfer) | [Video](https://drive.google.com/file/d/1BwUiPkOwn5pLpoLQ2dVjDs5ooAYvZ1Cl/view?usp=sharing) |

> John Guilding also explored 3 additional projects: [Private Prediction Market (Noir)](https://github.com/JohnGuilding/private-prediction-market-noir), [Canton on Base](https://github.com/JohnGuilding/canton-eth-base), [Canton on Aztec](https://github.com/JohnGuilding/canton-eth-aztec)

## Judging Criteria

| Criterion | Weight | Description |
|-----------|--------|-------------|
| Usefulness | 30% | Does this solve a real problem? Would people actually use it? |
| Working demo | 25% | Does it work? Can you show it running? |
| Creativity | 20% | Is the idea novel or surprising? |
| Implementation quality | 15% | Is the code reasonable? Could someone pick this up after the hackathon? |
| Presentation | 10% | Was the demo clear and compelling? |

## Prizes

| Place | Prize |
|-------|-------|
| 1st | $1,200 |
| 2nd | $500 |
| 3rd | $300 |

## Coordination

- **Mattermost channel**: [Vibecoding Hackathon Feb 2026](https://chat.ethereum.foundation/pse/channels/ai-hackathon-feb-2026)
