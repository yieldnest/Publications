# YieldNest Monthly Report – ynUSDx (June 2026)

![](https://raw.githubusercontent.com/yieldnest/Publications/refs/heads/main/assets/ynUSDx/report.png)

---

**Vault Asset**: ynUSDx
**Vault Chain**: Ethereum Chain
**Vault Type**: MAX
**Vault Launch Date**: June 2025
**Period Covered:** June 1 – June 30, 2026
**Report Date:** July 1, 2026

---

## 1. Executive Summary

[ynUSDx](https://app.yieldnest.finance/token/ynUSDx) is YieldNest's MAX product deployed on Ethereum Chain. It auto-compounds USD yield through DeFi-native strategies, offering liquid exposure and ETH L1 settlement.

_Return accrues as the value of ynUSDx increases relative to USDC._

---

## 2. Vault Overview Report (as of July 1, 2026)

### Monthly Overview Report

- Vault TVL: $353,179.90
- APY stats from June:
    - 2026-06-23 - 2026-06-30: 12.38%
    - 2026-06-01 - 2026-06-30: 10.01%

---

## 3. Strategy Breakdown (as of July 1, 2026)

| Asset / Strategy | Allocation | Protocol | Description |
| --- | --- | --- | --- |
| USDC Arbitrage | 58.00% | YieldNest | Delta Neutral Arbitrage Strategy compounding rewards in USDC. |
| USDC Lending | 37.59% | Euler | Earns rewards by lending USDC on Euler to borrow against ynRWAx. |
| USDC | 3.46% | – | Freshly deposited USDC, held as idle capital and ready to be deployed into yield or arbitrage strategies. |
| USDC RWA Lending | 0.95% | Morpho | Earns rewards by lending USDC on Morpho to the YieldNest RWA market while supporting instant withdrawals for ynUSDx. |

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

## 5. Outlook & Strategy Notes

- Optimized reward collection to improve yield efficiency and auto-compounding
