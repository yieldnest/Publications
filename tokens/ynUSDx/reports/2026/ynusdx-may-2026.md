# YieldNest Monthly Report – ynUSDx (May 2026)

![](https://raw.githubusercontent.com/yieldnest/Publications/refs/heads/main/assets/ynUSDx/report.png)

---

**Vault Asset**: ynUSDx
**Vault Chain**: Ethereum Chain
**Vault Type**: MAX
**Vault Launch Date**: June 2025
**Period Covered:** May 1 – May 31, 2026
**Report Date:** June 1, 2026

---

## 1. Executive Summary

[ynUSDx](https://app.yieldnest.finance/token/ynUSDx) is YieldNest's MAX product deployed on Ethereum Chain. It auto-compounds USD yield through DeFi-native strategies, offering liquid exposure and ETH L1 settlement.

_Return accrues as the value of ynUSDx increases relative to USDC._

---

## 2. Vault Overview Report (as of June 1, 2026)

### Monthly Overview Report

- Vault TVL: $348,160.21
- APY stats from May:
    - 2026-05-24 - 2026-05-31: 17.34%
    - 2026-05-01 - 2026-05-31: 9.00%

---

## 3. Strategy Breakdown (as of June 1, 2026)

| Asset / Strategy | Allocation | Protocol | Description |
| --- | --- | --- | --- |
| USDC Arbitrage | 58.47% | YieldNest | Delta Neutral Arbitrage Strategy compounding rewards in USDC. |
| USDC Lending | 37.63% | Euler | Earns rewards by lending USDC on Euler to borrow against ynRWAx. |
| USDC RWA Lending | 2.96% | Morpho | Earns rewards by lending USDC on Morpho to the YieldNest RWA market while supporting instant withdrawals for ynUSDx. |
| USDC | 0.95% | – | Freshly deposited USDC, held as idle capital and ready to be deployed into yield or arbitrage strategies. |

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

- ✅ [YieldNest Partners with Willow Protocol for Cryptographically Verifiable Analytics Dashboard](https://x.com/YieldNestFi/status/2066330444204040694)

## 6. Outlook & Strategy Notes

- Optimized reward collection to improve yield efficiency and auto-compounding
