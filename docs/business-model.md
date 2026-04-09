# Business Model

## Revenue streams

| Stream | At launch (V1) | At scale (V3+) |
|--------|---------------|----------------|
| Performance fee | 10% of yield above hurdle | 15% |
| Curation fee | 0% | 5 bps on AUM |
| Oracle fees (V3) |. | Flat monthly + per-tx on third-party vaults |

50% of performance fees at launch are directed toward TVL growth incentives. TVL first.

Lagoon can activate a protocol fee up to 30% of curator fees. Currently no vault is subject to protocol fees. This is one reason Agama builds its own protocol at V3.

## Echelon

| AUM | Phase | Revenue | Status |
|-----|-------|---------|--------|
| 1M | V1 | ~10k/yr | Bootstrap. Rayls grant covers development |
| 10M | V2 | ~100k/yr | Product-market fit confirmed. Expand vault pipeline |
| 100M | V3 | ~500k/yr + oracle fees | Fully self-funded. Independent protocol. Oracle network live |
| 500M | V4 | ~2.5M/yr + oracle fees + token | agaUSD live. $AGA token |

No fundraising required for V1. The Rayls development grant and Nimofast onboarding fees cover the initial build.

## V3 revenue model shift

At V1-V2, revenue comes from curator fees on Agama's own vaults. This is real but not defensible: any team can build a competing vault on Lagoon.

At V3, revenue shifts to oracle fees. Every third-party vault that reads private asset NAV through an Agama Node pays oracle fees. This is recurring, infrastructure-level revenue independent of Agama's own AUM. Even if Agama stops curating vaults entirely, the oracle network generates fees.

```
V1-V2 revenue:
  10% performance fee × vault AUM
  Dependent on Agama's own TVL
  Defensible only through first-mover advantage

V3+ revenue:
  Oracle fees on EVERY vault using Agama Nodes
  Independent of Agama's own TVL
  Defensible through structural moat
  (view key access = non-replaceable)
```
