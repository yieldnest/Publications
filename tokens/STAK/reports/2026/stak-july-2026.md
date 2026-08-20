# YieldNest Monthly Report – STAK (July 2026)

![](https://raw.githubusercontent.com/yieldnest/Publications/refs/heads/main/assets/STAK/report.png)

---

**Vault Asset**: STAK
**Vault Chain**: Ethereum Chain
**Vault Type**: MAX
**Vault Launch Date**: December 2025
**Period Covered:** July 1 – July 31, 2026
**Report Date:** August 1, 2026

---

## 1. Executive Summary

[STAK](https://app.yieldnest.finance/token/STAK) is YieldNest's MAX product deployed on Ethereum Chain. It auto-compounds USD yield through DeFi-native strategies, offering liquid exposure and ETH L1 settlement.

_Return accrues as the value of STAK increases relative to USDC._

---

## 2. Vault Overview Report (as of August 1, 2026)

### Monthly Overview Report

- Vault TVL: $260,771.60
- APY stats from July:
    - 2026-07-24 - 2026-07-31: 0.15%
    - 2026-07-01 - 2026-07-31: 4.17%

---

## 3. Strategy Breakdown (as of August 1, 2026)

| Asset / Strategy | Allocation | Protocol | Description |
| --- | --- | --- | --- |
| Stake DAO ynRWAx/ynUSDx | 100.00% | StakeDAO | This strategy automatically stakes your yn-RWA/USD in the Curve gauge, and boosts it thanks to the veCRV position owned by the CRV Liquid Locker. |

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
