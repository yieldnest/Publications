# YieldNest Monthly Report – ynUSDx (April 2026)

![](https://raw.githubusercontent.com/yieldnest/Publications/refs/heads/main/assets/ynUSDx/report.png)

---

**Vault Asset**: ynUSDx
**Vault Chain**: Ethereum Chain
**Vault Type**: MAX
**Vault Launch Date**: June 2025
**Period Covered:** April 1 – April 30, 2026
**Report Date:** May 1, 2026

---

## 1. Executive Summary

[ynUSDx](https://app.yieldnest.finance/token/ynUSDx) is YieldNest's MAX product deployed on Ethereum Chain. It auto-compounds USD yield through DeFi-native strategies, offering liquid exposure and ETH L1 settlement.

_Return accrues as the value of ynUSDx increases relative to USDC._

---

## 2. Vault Overview Report (as of May 1, 2026)

### Monthly Overview Report

- Vault TVL: $921,998.97
- APY stats from April:
    - 2026-04-23 - 2026-04-30: 7.73%
    - 2026-04-01 - 2026-04-30: 4.99%

---

## 3. Strategy Breakdown (as of May 1, 2026)

| Asset / Strategy | Allocation | Protocol | Description |
| --- | --- | --- | --- |
| USDC Lending | 58.97% | Euler | Earns rewards by lending USDC on Euler to borrow against ynRWAx. |
| USDC | 21.55% | – | Freshly deposited USDC, held as idle capital and ready to be deployed into yield or arbitrage strategies. |
| USDC Arbitrage | 11.11% | YieldNest | Delta Neutral Arbitrage Strategy compounding rewards in USDC. |
| USDC RWA Lending | 8.37% | Morpho | Earns rewards by lending USDC on Morpho to the YieldNest RWA market while supporting instant withdrawals for ynUSDx. |

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

- ✅ [$ynRWAx Surpasses $8M TVL](https://x.com/YieldNestFi/status/2039198067229085962)

## 6. Outlook & Strategy Notes

- Optimized reward collection to improve yield efficiency and auto-compounding
