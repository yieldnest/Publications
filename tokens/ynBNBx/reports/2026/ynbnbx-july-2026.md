# YieldNest Monthly Report – ynBNBx (July 2026)

![](https://raw.githubusercontent.com/yieldnest/Publications/refs/heads/main/assets/ynBNBx/report.png)

---

**Vault Asset**: ynBNBx
**Vault Chain**: BNB Chain
**Vault Type**: MAX
**Vault Launch Date**: December 2024
**Period Covered:** July 1 – July 31, 2026
**Report Date:** August 1, 2026

---

## 1. Executive Summary

[ynBNBx](https://app.yieldnest.finance/token/ynBNBx) is YieldNest's MAX product deployed on BNB Chain. It auto-compounds BNB yield through Binance rewards and DeFi-native strategies, offering liquid exposure and BNB L1 settlement.

Starting in 2025 August, reward collection has been optimized to automatically convert and compound rewards into BNB, further enhancing yield efficiency.

*Return accrues as the value of ynBNBx increases relative to BNB.*

---

## 2. Vault Overview Report (as of August 1, 2026)

### Monthly Overview Report

- Vault TVL: $80,330.76 (136.78 WBNB)
- Yield Generated: $0 (0 WBNB)
- APY stats from July:
    - 2026-07-24 - 2026-07-31: 0.01%
    - 2026-07-01 - 2026-07-31: 0.14%

---

## 3. Strategy Breakdown (as of August 1, 2026)

| Asset / Strategy | Allocation | Protocol | Description |
| --- | --- | --- | --- |
| wBNB | 60.10% | - | Freshly deposited wBNB ready to be deployed into strategies. |
| ynBNBx Lending | 39.36% | AAVE | Earns yield by lending WBNB on AAVE, while supporting instant withdrawals for ynBNBx. |
| ynClisBNB | 0.54% | YieldNest | ynClisBNB is a proprietary Yieldnest strategy that earns rewards from Binance Launchpool, Megadrop, and HODLer Airdrop. |

---

## 4. Yield Generation Breakdown (as of August 1, 2026)

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
