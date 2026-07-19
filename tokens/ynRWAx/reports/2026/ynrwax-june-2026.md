# YieldNest Monthly Report – ynRWAx (June 2026)

![](https://raw.githubusercontent.com/yieldnest/Publications/refs/heads/main/assets/ynRWAx/report.png)

---

**Vault Asset**: ynRWAx
**Vault Chain**: Ethereum Chain
**Vault Type**: MAX
**Vault Launch Date**: June 2025
**Period Covered:** June 1 – June 30, 2026
**Report Date:** July 1, 2026

---

## 1. Executive Summary

[ynRWAx](https://app.yieldnest.finance/token/ynRWAx) is YieldNest's MAX product deployed on Ethereum Chain. It auto-compounds USD yield through RWA-native strategies, offering liquid exposure and ETH L1 settlement.

_Return accrues as the value of ynRWAx increases relative to USDC._

---

## 2. Vault Overview Report (as of July 1, 2026)

### Monthly Overview Report

- Vault TVL: $9,233,298.60
- APY stats from June:
    - 2026-06-23 - 2026-06-30: 13.32%
    - 2026-06-01 - 2026-06-30: 11.28%

---

## 3. Strategy Breakdown (as of July 1, 2026)

| Asset / Strategy | Allocation | Protocol | Description |
| --- | --- | --- | --- |
| MAX RWA | 99.92% | - | Rewards are generated from real estate backed credit strategies managed by Kimber Capital. ynRWAx may be redeemed for a 7 day period upon maturity. Upon completion of the redemption period, an automatic roll over will take place. MAX RWA is capped to be no more than 5% of the gross LTV of a diversified pool of secured RWA credit with full recourse. |
| USDC | 0.08% | – | Freshly deposited USDC, held as idle capital and ready to be deployed into yield or arbitrage strategies. |

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
