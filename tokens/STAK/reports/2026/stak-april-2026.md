# YieldNest Monthly Report – STAK (April 2026)

![](https://raw.githubusercontent.com/yieldnest/Publications/refs/heads/main/assets/STAK/report.png)

---

**Vault Asset**: STAK
**Vault Chain**: Ethereum Chain
**Vault Type**: MAX
**Vault Launch Date**: December 2025
**Period Covered:** April 1 – April 30, 2026
**Report Date:** May 1, 2026

---

## 1. Executive Summary

[STAK](https://app.yieldnest.finance/token/STAK) is YieldNest's MAX product deployed on Ethereum Chain. It auto-compounds USD yield through DeFi-native strategies, offering liquid exposure and ETH L1 settlement.

_Return accrues as the value of STAK increases relative to USDC._

---

## 2. Vault Overview Report (as of May 1, 2026)

### Monthly Overview Report

- Vault TVL: $279,858.97
- APY stats from April:
    - 2026-04-23 - 2026-04-30: 10.22%
    - 2026-04-01 - 2026-04-30: 8.08%

---

## 3. Strategy Breakdown (as of May 1, 2026)

| Asset / Strategy | Allocation | Protocol | Description |
| --- | --- | --- | --- |
| Stake DAO ynRWAx/ynUSDx | 99.70% | StakeDAO | This strategy automatically stakes your yn-RWA/USD in the Curve gauge, and boosts it thanks to the veCRV position owned by the CRV Liquid Locker. |
| ynRWAx/ynUSDx | 0.30% | Curve | Freshly deposited LP token, held as idle capital and ready to be deployed into strategies. |

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
