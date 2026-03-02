# YieldNest Monthly Report – ynUSDx (January 2026)

![](https://raw.githubusercontent.com/yieldnest/Publications/refs/heads/main/assets/ynUSDx/report.png)

---

**Vault Asset**: ynUSDx
**Vault Chain**: Ethereum Chain
**Vault Type**: MAX
**Vault Launch Date**: June 2025
**Period Covered:** January 1 – January 31, 2026
**Report Date:** February 1, 2026

---

## 1. Executive Summary

[ynUSDx](https://app.yieldnest.finance/token/ynUSDx) is YieldNest’s MAX product deployed on Ethereum Chain. It auto-compounds USD yield through DeFi-native strategies, offering liquid exposure and ETH L1 settlement.

_Return accrues as the value of ynUSDx increases relative to USDC._

---

## 2. Vault Overview Report (as of February 1, 2026)

### Monthly Overview Report

- Vault TVL: $372,975.60
- APY stats from January:
  - 2026-01-24 - 2026-01-31: 7.98%
  - 2026-01-01 - 2026-01-31: 5.91%

---

## 3. Strategy Breakdown (as of February 1, 2026)

| Asset / Strategy | Allocation | Protocol      | Description                                                                                                                                    |
| ---------------- | ---------- | ------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| USDC             | 12.40%     | –             | Freshly deposited USDC, held as idle capital and ready to be deployed into yield or arbitrage strategies.                                      |
| USDC Lending     | 12.82%     | Morpho        | Earns yield by lending USDC on Morpho with Gauntlet risk management, while supporting instant withdrawals for ynUSDx.                          |
| USDC Lending     | 0.00%      | Euler         | Earns yield by lending USDC on Euler, enabling borrowing against ynRWAx.                                                                       |
| USDC Arbitrage   | 26.88%     | YieldNest     | Delta-neutral arbitrage strategy that compounds protocol and market incentives while maintaining USDC exposure.                                |
| Super USDC       | 29.89%     | Superform     | Optimizes USDC returns across blue-chip Ethereum lending protocols by automatically rebalancing between vaults using predictive on-chain data. |
| f(x) USD Saving  | 18.00%     | f(x) Protocol | fxSAVE is a high-yield, auto-compounding delta-neutral stablecoin vault managed by f(x) Protocol.                                              |

---

## 4. Security & Risk Monitoring

Audited Completed:

- [Zokyo - Dec 2024](https://github.com/yieldnest/Publications/blob/main/audits/zokyo_audit_yieldnest_dec12th_2024.pdf)
- [Composable Security - Jan 2025](https://github.com/yieldnest/Publications/blob/main/audits/composable_security_yieldnest_jan_2025.pdf)
- [Llamarisk - Jan 2025](https://www.llamarisk.com/research/asset-risk-ynbnbx)
- [NFR Audits Feb 2025](https://github.com/yieldnest/Publications/blob/main/audits/yieldnest_max_vault_withdrawer_audit_report.pdf)

On-Chain Protections:

- ERC-4626 modular vaults
- Strategy whitelisting via Guard Engine
- Proxy upgrade system
- Bounded execution for slashing/misallocation defense

---

## 5. Notable Events This Month

- ✅ [Introducing STAK: RWA + DeFi Yield, Unified in One Token](https://x.com/YieldNestFi/status/2011381260833444324)
- ✅ [YieldNest Delegator Launches on CAP: Institutional-Grade Restaking Meets RWAs](https://x.com/YieldNestFi/status/2014626348711735736)
- ✅ [Incentra Campaign Returns: Earn STAK by Holding YieldNest’s New RWA + DeFi Product](https://x.com/YieldNestFi/status/2015081270964085026)
- ✅ [ynRWAx Ranks Among Top Stablecoin Vaults with ~11% APY and Instant Liquidity](https://x.com/YieldNestFi/status/2016858373455818919)

## 6. Outlook & Strategy Notes

- Optimized reward collection to improve yield efficiency and auto-compounding
