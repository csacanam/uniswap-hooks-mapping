# Mapping Uniswap Hook Incubator Winners to Community Requests for Hooks

This repository maps ~80 prize-winning Uniswap v4 hooks from Atrium’s **Uniswap Hook Incubator** to the categories listed in Atrium’s **Requests for Hooks (RFH)**.  

The goal is to identify which RFH ideas are already being addressed and which remain largely unexplored.

⚠ **Disclaimer:** This mapping was created with ChatGPT Agent Mode. It may contain errors or debatable classifications. Contributions, corrections, and additional examples are welcome.

## Context

- **Hook Incubator Winners:** The hooks analysed here are **prize winners** from previous *Hookathons* organised by [Atrium](https://hooks.atrium.academy/) under the **Uniswap Hook Incubator** program.  
- **Requests for Hooks (RFH):** The RFH list is published by [Atrium](https://rfh.atrium.academy/) and contains ideas submitted by third parties about specific hook needs — such as dynamic fee models, MEV mitigation, gamified incentives, or rehypothecation.

By cross-checking these two sources, we can see which RFH categories have prize-winning implementations and where there are still white-space opportunities.

## Coverage by RFH

| RFH Category | Examples of Hooks | Approx. # of Prize-Winning Hooks | Share* |
| ----- | ----- | :---: | :---: |
| Gamified incentives & rewards | Degen Options, Concentrated Incentives, Catapoolt, TradeBattle, Omni Incentive Hook, Yield Matcha, Liquidity Rewards, DegenSwap, RaffleSwap, Milady Pool, Memediction, PointPool | ~12 | ~15% |
| MEV mitigation & internalised MEV | MEV Auction Hook, FrontrunThis, Sandwich Protector, Detozer MEV suite, Lever (LVR auctions), EigenLVR, LP Hub | 7 | ~8.8% |
| Dynamic fee models | FlexFee (volatility-based fees), LP Hub (VPIN-based), RWEEventHook – Dynamic Fee, ember (volatility-based), Uniq (RWA volatility fees), Fidelity Hook | 6 | ~7.5% |
| Derivatives (options/futures/volatility) | Degen Options, Lumis, YOLO Protocol, SkySwap, VixDex, Fixed/Leverage Yield Hook, PerpDexHook | 7 | ~8.8% |
| Auto-position rebalancing / liquidity management | Autopilot Hook, Advanced Liquidity Manager, Dynamic LP Assurance, LP Hub | 4 | ~5% |
| Rehypothecation / idle liquidity yield | Chook, Idle Liquidity Yield Earning Hook, CoPool, RwAsync Swap | 4 | ~5% |
| Auto-hedging & IL protection | SkySwap – IL-Free CLMM, Dynamic LP Assurance, Gainswap, UNIV4-Risk-Neutral Hook | 4 | ~5% |
| Internalised MEV / auction-managed AMM | MEV Auction Hook, EigenLVR, Auction Managed AMM & Active Range, Lever | 4 | ~5% |
| Custom curve / peg design | SkySwap (dynamic peg), UniCow v2, Gainswap | 3 | ~3.8% |
| Oracle / data hooks | Liquidity Oracle, DynamicShield Hook, ViFi | 3 | ~3.8% |
| Permissioned pools / KYC | kvhook, KYC Hook | 2 | ~2.5% |
| Lending within the AMM (oracle-less) | Debt Hook, LPDAO – Hedge Fund in a Hook | 2 | ~2.5% |
| Auction-managed incentivisation | EigenLVR, Auction Managed AMM & Active Range | 2 | ~2.5% |
| Cross-chain arbitrage / CoW | CrossLink, CowSwap Hook | 2 | ~2.5% |
| RWA & real-time FX | OriginateX + Passthru Protocol, Uniq | 2 | ~2.5% |
| Token fee claiming / Flaunch staking | Blueprint, Flaunch-lazy-lp | 2 | ~2.5% |
| Cross-chain gas price optimisation | Cross-Chain Gas Price Optimisation Hook | 1 | ~1.3% |
| Gasless swaps (pay fees in USDC) | PayWithUsdc | 1 | ~1.3% |
| Tornado-style mixing | Vortex Protocol | 1 | ~1.3% |
| Hook safety / monitoring | UniGuard | 1 | ~1.3% |
| LRT / LST liquidity | UniCast | 1 | ~1.3% |
| CEX/DEX order book merge | V4-orderbook | 1 | ~1.3% |
| **Zero coverage** | Gas Price Fees, JIT Rebalancing, Nezlobin’s Directional Fee, LAMMBert curve, TWAMM, Keeper Activity Hook, UniBrain, targeted liquidity, advanced cross-chain oracles, auto-replenishing USDC pools, streaming USDC rewards, migration adapters, discovery launchpads | 0 | 0% |

\*Percentages assume ~80 prize-winning hooks.

## Key Observations

- **Most covered:** Gamified incentives, dynamic fee models, MEV protection, derivatives/insurance.
- **Least covered:** Gas-price-based fees, JIT rebalancing, advanced cross-chain state sharing, TWAMM, Lambert W curves.
- **Opportunity:** Combine popular categories with underexplored ones to stand out in future hookathons.
- **Integration trend:** Growing use of EigenLayer AVS, Brevis, Circle, Across, Flaunch.

## How to Contribute

- Review the mappings and suggest corrections or additional examples.
- Open an **issue** for misclassifications or missing categories.
- Submit a **pull request** to expand descriptions or add links.

---

*Sources:*  
- Hook Incubator Winners: [https://hooks.atrium.academy/](https://hooks.atrium.academy/)  
- Requests for Hooks: [https://rfh.atrium.academy/](https://rfh.atrium.academy/)  

*Compiled with ChatGPT Agent Mode – may contain errors.*
