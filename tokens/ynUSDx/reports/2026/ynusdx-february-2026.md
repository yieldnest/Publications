# YieldNest Monthly Report – ynUSDx (February 2026)

![](https://raw.githubusercontent.com/yieldnest/Publications/refs/heads/main/assets/ynUSDx/report.png)


---

**Vault Asset**: ynUSDx
**Vault Chain**: Ethereum Chain
**Vault Type**: MAX
**Vault Launch Date**: June 2025
**Period Covered:** February 1 – February 28, 2026
**Report Date:** March 1, 2026

---

## 1. Executive Summary

[ynUSDx](https://app.yieldnest.finance/token/ynUSDx) is YieldNest’s MAX product deployed on Ethereum Chain. It auto-compounds USD yield through DeFi-native strategies, offering liquid exposure and ETH L1 settlement.

*Return accrues as the value of ynUSDx increases relative to USDC.*

---

## 2. Vault Overview Report (as of March 1, 2026)

### Monthly Overview Report

* Vault TVL: $502,857.21
* APY stats from February:
    * 2026-02-21 - 2026-02-28: 7.00%
    * 2026-02-01 - 2026-02-28: 5.64%

---

## 3. Strategy Breakdown (as of March 1, 2026)


| Asset / Strategy    | Allocation | Protocol      | Description |
| ------------------- | ---------- | ------------- | --------------------------------- |
| USDC            | 1.39%     | –             | Freshly deposited USDC, held as idle capital and ready to be deployed into yield or arbitrage strategies.                                      |
| USDC Lending    | 0.01%     | Morpho        | Earns yield by lending USDC on Morpho with Gauntlet risk management, while supporting instant withdrawals for ynUSDx.                          |
| USDC Lending    | 64.78%      | Euler         | Earns yield by lending USDC on Euler, enabling borrowing against ynRWAx.                                                                       |
| USDC Arbitrage  | 20.08%     | YieldNest     | Delta-neutral arbitrage strategy that compounds protocol and market incentives while maintaining USDC exposure.                                |
| Super USDC      | 0.34%     | Superform     | Optimizes USDC returns across blue-chip Ethereum lending protocols by automatically rebalancing between vaults using predictive on-chain data. |
| f(x) USD Saving | 13.40%     | f(x) Protocol | fxSAVE is a high-yield, auto-compounding delta-neutral stablecoin vault managed by f(x) Protocol.                                              |

---

## 4. Security & Risk Monitoring

Audited Completed:

* [Zokyo - Dec 2024](https://github.com/yieldnest/Publications/blob/main/audits/zokyo_audit_yieldnest_dec12th_2024.pdf)
* [Composable Security - Jan 2025](https://github.com/yieldnest/Publications/blob/main/audits/composable_security_yieldnest_jan_2025.pdf)
* [Llamarisk - Jan 2025](https://www.llamarisk.com/research/asset-risk-ynbnbx)
* [NFR Audits Feb 2025](https://github.com/yieldnest/Publications/blob/main/audits/yieldnest_max_vault_withdrawer_audit_report.pdf)

On-Chain Protections:
* ERC-4626 modular vaults
* Strategy whitelisting via Guard Engine
* Proxy upgrade system
* Bounded execution for slashing/misallocation defense

---

## 5. Notable Events This Month

* ✅ [YieldNest Yield Season: Multi-Protocol Incentives Now Live](https://x.com/YieldNestFi/status/2021841916904845804)
* ✅ [ynRWAx Surpasses $3M TVL Milestone](https://x.com/YieldNestFi/status/2024122556924780841)

## 6. Outlook & Strategy Notes

* Optimized reward collection to improve yield efficiency and auto-compounding