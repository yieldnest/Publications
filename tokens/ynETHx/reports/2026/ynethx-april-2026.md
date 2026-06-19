# YieldNest Monthly Report – ynETHx (April 2026)

![](https://raw.githubusercontent.com/yieldnest/Publications/refs/heads/main/assets/ynETHx/report.png)

---

**Vault Asset**: ynETHx
**Vault Chain**: Ethereum Chain
**Vault Type**: MAX
**Vault Launch Date**: November 2024
**Period Covered:** April 1 – April 30, 2026
**Report Date:** May 1, 2026

---

## 1. Executive Summary

[ynETHx](https://app.yieldnest.finance/token/ynETHx) is YieldNest's MAX product deployed on Ethereum Chain. It auto-compounds ETH yield through DeFi-native strategies, offering liquid exposure and ETH L1 settlement.

_Return accrues as the value of ynETHx increases relative to ETH._

---

## 2. Vault Overview Report (as of May 1, 2026)

### Monthly Overview Report

- Vault TVL: $9,906,090.48 (4,384.62 WETH)
- APY stats from April:
    - 2026-04-23 - 2026-04-30: 2.92%
    - 2026-04-01 - 2026-04-30: 4.09%

---

## 3. Strategy Breakdown (as of May 1, 2026)

| Asset / Strategy | Allocation | Protocol | Description |
| --- | --- | --- | --- |
| wstETH / ynRWAx | 79.80% | AAVE | Supply wstETH on Aave, borrow USD to deposit into ynRWAx. |
| ETH Arbitrage | 18.78% | YieldNest | Delta Neutral Arbitrage Strategy compounding rewards in ETH. |
| ynETHx Withdrawer | 1.35% | YieldNest | Current assets that are in the withdrawal queue. |
| wstETH | 0.07% | Lido | Lido wrapped staked ETH |

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
