# YieldNest Monthly Report – ynETHx (May 2026)

![](https://raw.githubusercontent.com/yieldnest/Publications/refs/heads/main/assets/ynETHx/report.png)

---

**Vault Asset**: ynETHx
**Vault Chain**: Ethereum Chain
**Vault Type**: MAX
**Vault Launch Date**: November 2024
**Period Covered:** May 1 – May 31, 2026
**Report Date:** June 1, 2026

---

## 1. Executive Summary

[ynETHx](https://app.yieldnest.finance/token/ynETHx) is YieldNest's MAX product deployed on Ethereum Chain. It auto-compounds ETH yield through DeFi-native strategies, offering liquid exposure and ETH L1 settlement.

_Return accrues as the value of ynETHx increases relative to ETH._

---

## 2. Vault Overview Report (as of June 1, 2026)

### Monthly Overview Report

- Vault TVL: $8,343,433.15 (4,154.99 WETH)
- APY stats from May:
    - 2026-05-24 - 2026-05-31: 6.03%
    - 2026-05-01 - 2026-05-31: 4.68%

---

## 3. Strategy Breakdown (as of June 1, 2026)

| Asset / Strategy | Allocation | Protocol | Description |
| --- | --- | --- | --- |
| wstETH / ynRWAx | 84.57% | AAVE | Supply wstETH on Aave, borrow USD to deposit into ynRWAx. |
| ETH Arbitrage | 15.09% | YieldNest | Delta Neutral Arbitrage Strategy compounding rewards in ETH. |
| WETH | 0.27% | - | Freshly deposited wETH ready to be deployed into strategies. |
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

- ✅ [YieldNest Partners with Willow Protocol for Cryptographically Verifiable Analytics Dashboard](https://x.com/YieldNestFi/status/2066330444204040694)

## 6. Outlook & Strategy Notes

- Optimized reward collection to improve yield efficiency and auto-compounding
