# YieldNest Monthly Report – ynBNBx (June 2026)

![](https://raw.githubusercontent.com/yieldnest/Publications/refs/heads/main/assets/ynBNBx/report.png)

---

**Vault Asset**: ynBNBx
**Vault Chain**: BNB Chain
**Vault Type**: MAX
**Vault Launch Date**: December 2024
**Period Covered:** June 1 – June 30, 2026
**Report Date:** July 1, 2026

---

## 1. Executive Summary

[ynBNBx](https://app.yieldnest.finance/token/ynBNBx) is YieldNest's MAX product deployed on BNB Chain. It auto-compounds BNB yield through Binance rewards and DeFi-native strategies, offering liquid exposure and BNB L1 settlement.

Starting in 2025 August, reward collection has been optimized to automatically convert and compound rewards into BNB, further enhancing yield efficiency.

*Return accrues as the value of ynBNBx increases relative to BNB.*

---

## 2. Vault Overview Report (as of July 1, 2026)

### Monthly Overview Report

- Vault TVL: $83,122.03 (152.31 WBNB)
- Yield Generated: $0 (0 WBNB)
- APY stats from June:
    - 2026-06-23 - 2026-06-30: 1.18%
    - 2026-06-01 - 2026-06-30: 0.29%

---

## 3. Strategy Breakdown (as of July 1, 2026)

| Asset / Strategy | Allocation | Protocol | Description |
| --- | --- | --- | --- |
| wBNB | 53.97% | - | Freshly deposited wBNB ready to be deployed into strategies. |
| ynBNBx Lending | 45.55% | AAVE | Earns yield by lending WBNB on AAVE, while supporting instant withdrawals for ynBNBx. |
| ynClisBNB | 0.48% | YieldNest | ynClisBNB is a proprietary Yieldnest strategy that earns rewards from Binance Launchpool, Megadrop, and HODLer Airdrop. |

---

## 4. Yield Generation Breakdown (as of July 1, 2026)

**Total Airdrop Yield (WBNB): 0 WBNB**

---

## 5. Security & Risk Monitoring

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

## 6. Outlook & Strategy Notes

- Optimized reward collection to improve yield efficiency and auto-compounding
