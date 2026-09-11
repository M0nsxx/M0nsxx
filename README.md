# Monserrat Mendoza (`M0nsxx`)

Cofounder, with [Giovanny](https://github.com/Eras256), of six projects
across four chains — UX/UI across every one of them, and backend dev
too (five merged PRs, detail below).

| Project(s) | Chain | Why there |
| --- | --- | --- |
| Kumply | Avalanche | Compliance for regulated institutions: purpose-built [Evergreen Subnets](https://www.avax.network/about/blog/avalanche-launches-evergreen-for-institutional-blockchain-deployments/) give KYC, permissioned validators, and controlled access |
| Vouch402 | Base | Where the x402 agent-payment volume already is: an independent census puts [98.44% of all published x402 resources on Base](https://github.com/arturete58-sys/x402-observatory/blob/main/report-01-census.md) |
| Prova | Solana | [Sub-second finality, ~$0.0004–0.0005 per transaction](https://solana.com/docs/core/fees) — the cost profile a high-frequency agent-receipt layer needs |
| Periplo, Nirium, Contextio | Stellar | Payments: [$0.0007667 average transaction cost](https://stellar.org/) and 24/7 settlement, cheap enough for agent-scale micropayments, plus the SCF funding program this portfolio started in |

I write this with the same rule Giovanny uses on his own profile: if a
claim here can't be clicked and checked, it doesn't belong here. I'm a
backend dev and UX/UI by background, not just UX/UI — but most of these
projects haven't needed my code yet, so my visible contribution there is
still UX/UI, not commits. Nirium is the one place that's shown up in
actual merged PRs so far (five of them). Stated as that, not padded to
look like something it isn't.

---

## Highlights

Skip the rest if you only have 90 seconds:

- **Five merged PRs in [`nirium-protocol/nirium`](https://github.com/nirium-protocol/nirium)** —
  my own shipped code, not a design contribution described in code
  terms: a resilient reconnecting WebSocket signals client, CLI
  `pay`/`serve` commands for x402, a one-click "Deploy to Vercel" x402
  API template, a `nirium doctor` preflight diagnostic command, and a
  standalone offline audit-CID/Ed25519 attestation verifier. Each closes
  a real GrantFox bounty issue, all merged by [@Eras256](https://github.com/Eras256) —
  full table below.
- **Prova (cofounded) took 1st place in Mexico at the Dev3Pack Global
  Hackathon** and graduated WayLearn's Solana Foundation-backed Solana
  Latam Labs Program — full detail and links in the Prova row below.
- **Where I haven't personally shipped code, this profile says so
  plainly** instead of implying otherwise — the honesty standard applies
  to my own side of the work too, not just Giovanny's.
- **Two hackathon wins outside this portfolio too, both with Giovanny,
  both with a public tweet confirming them** — ActivaChain (ETH Uruguay
  2025) and BioShield Insurance (FDA Track, DeSci Builders Hackathon
  2025). Full detail near the bottom.

---

## Verified contributions

### Merged PRs — [`nirium-protocol/nirium`](https://github.com/nirium-protocol/nirium)

My own shipped code, not a design contribution described in code terms —
all five authored by me, merged by [@Eras256](https://github.com/Eras256), each
closing a [GrantFox OSS](https://grantfox.io) bounty issue.

| PR | Closes | Title | Merged |
| --- | --- | --- | --- |
| [#58](https://github.com/nirium-protocol/nirium/pull/58) | [#50](https://github.com/nirium-protocol/nirium/issues/50) | "Deploy to Vercel" one-click x402-protected API template | 2026-08-24 |
| [#59](https://github.com/nirium-protocol/nirium/pull/59) | [#37](https://github.com/nirium-protocol/nirium/issues/37) | `nirium doctor` CLI preflight diagnostic command | 2026-08-25 |
| [#61](https://github.com/nirium-protocol/nirium/pull/61) | [#45](https://github.com/nirium-protocol/nirium/issues/45) | Resilient reconnecting WebSocket signals client | 2026-08-25 |
| [#60](https://github.com/nirium-protocol/nirium/pull/60) | [#38](https://github.com/nirium-protocol/nirium/issues/38) | Standalone offline audit-CID + Ed25519 attestation verifier | 2026-08-26 |
| [#62](https://github.com/nirium-protocol/nirium/pull/62) | [#44](https://github.com/nirium-protocol/nirium/issues/44) | CLI `pay` and `serve` commands for x402 | 2026-08-26 |

---

## What I work on

| Project | My role | Notes |
| --- | --- | --- |
| **[Kumply](https://github.com/kumplyprotocol/Kumply)** · [kumply.xyz](https://kumply.xyz) | UX/UI | On-chain KYC/KYB/KYA compliance attestations on Avalanche. Currently under review for Avalanche's Team1 Mini Grants. No commits under my handle yet — same honest disclosure as above. |
| **Vouch402** · [vouch402.xyz](https://www.vouch402.xyz) | UX/UI | x402-metered on-chain risk intelligence for agents on Base. Currently under review for Base Batches. Source at [`Vouch402/Vouchx402`](https://github.com/Vouch402/Vouchx402), now public. |
| **[Prova](https://github.com/Prova-Solana/Prova)** · [theprova.xyz](https://www.theprova.xyz) | UX/UI | Cryptographic on-chain receipts for AI agent actions on Solana. Solana devnet today, not mainnet. Built through two Colosseum hackathon cycles: [Prova](https://colosseum.com/arena/projects/explore/prova-1), and earlier [Oraculo](https://colosseum.com/arena/projects/explore/oraculo) at the Solana Cypherpunk Hackathon (Sep-Oct 2025), plus WayLearn's Solana Foundation-backed Solana Latam Labs Program (Jun-Aug 2026), taking 1st place in Mexico at the Dev3Pack Global Hackathon along the way. Applied for a Superteam/Solana Foundation scholarship to attend Breakpoint 2026 — decision pending. |
| **[Periplo](https://github.com/Eras256/Periplo)** · [periplo.xyz](https://periplo.xyz) | UX/UI | x402 payment facilitator for Stellar with a "Bazaar" discovery catalog. Cofounded; no PRs/issues under my own handle here yet — my contributions have run through pair sessions committed under Giovanny's account. |
| **[Nirium](https://github.com/Eras256/Nirium)** / [nirium](https://github.com/nirium-protocol/nirium) · [nirium.xyz](https://nirium.xyz) | Backend dev, UX/UI | Autonomous treasury and x402/MPP payments on Stellar. Five merged PRs above — my first shipped code on this portfolio. |
| **[Contextio](https://github.com/contextio/Contextio)** · [contextio.xyz](https://contextio.xyz) | UX/UI | AI agent moving treasury/payroll funds for LatAm SMEs, bound to a verifiable Legal Context Protocol document. Cofounded; contributions so far are design & strategy pair sessions, not commits under my handle. |

---

## My own projects — Stellar

### [VerifyStar](https://github.com/M0nsxx/VerifyStar) · [verify-star.vercel.app](https://verify-star.vercel.app)

Supply-chain transparency platform on Stellar/Soroban — product
tokenization, QR-based verification, and fair-trade escrow payments.
Next.js + Freighter wallet + Soroban smart contracts (Rust).

### [Stellar](https://github.com/M0nsxx/Stellar) · [StellarCodigoFutura](https://github.com/M0nsxx/StellarCodigoFutura)

Learning repos from the "Código Futura con Stellar" course — JS scripts
for account creation, payments, balance monitoring, and Soroban contract
invocation on testnet.

### [`M0nsxx/Nirium`](https://github.com/M0nsxx/Nirium) *(early prototype, inactive)*

Created 2026-03-21, last touched the same day. Describes early-vision
features (flash loans, ELO reputation, on-chain marketplace) that are
**not the current Nirium product** — the active codebase lives at
[`nirium-protocol/nirium`](https://github.com/nirium-protocol/nirium).

---

## Outside the portfolio

- **[ActivaChain](https://activachain.com)** — won ETH Uruguay 2025,
  cofounded with [Giovanny](https://github.com/Eras256). Confirmed by
  [the event's own tweet](https://x.com/EthereumUruguay/status/1968785973749170227):
  "Felicitaciones @ActivaChain! Nos representarán en Devconnect" — the
  top prize was a ticket + travel to Devconnect (Nov 2025).
- **[BioShield Insurance](https://bioshield-insurance.vercel.app/)** — won
  the FDA Track at the DeSci Builders Hackathon (Gitcoin × Infinita City
  × Próspera, Honduras, 2025), built with
  [Giovanny](https://github.com/Eras256). Deployed across Solana, Base,
  and Optimism. Self-reported — [his own
  tweet](https://x.com/vaiossx/status/1972064428091924681) at the time,
  not an organizer announcement.
- **[PakalFi](https://github.com/M0nsxx/PakalFi)** — DeFi project, Monad Mobil3 hackathon (CDMX).
- **[x402-Shield](https://github.com/M0nsxx/x402-Shield-)** — DDoS/Sybil defense via HTTP 402 micropayments (Solana).

---

## Stack

![Avalanche](https://img.shields.io/badge/Avalanche-E84142?style=flat-square&logo=avalanche&logoColor=white)
![Base](https://img.shields.io/badge/Base-0052FF?style=flat-square&logo=coinbase&logoColor=white)
![Stellar](https://img.shields.io/badge/Stellar-000000?style=flat-square&logo=stellar&logoColor=white)
![Soroban](https://img.shields.io/badge/Soroban-1f6feb?style=flat-square)
![Solana](https://img.shields.io/badge/Solana-9945FF?style=flat-square&logo=solana&logoColor=white)
![x402](https://img.shields.io/badge/x402-teal?style=flat-square)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)

---

## Full portfolio

The rest of the technical trail — contribution tables, transaction
hashes, contract addresses — lives on
[Giovanny's profile](https://github.com/Eras256/Eras256), since most of
it is his commits under his account. This page is my own side of the
same six projects.
