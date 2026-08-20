# YieldNest Monthly Report – ynETHx (July 2026)

![](https://raw.githubusercontent.com/yieldnest/Publications/refs/heads/main/assets/ynETHx/report.png)

---

**Vault Asset**: ynETHx
**Vault Chain**: Ethereum Chain
**Vault Type**: MAX
**Vault Launch Date**: November 2024
**Period Covered:** July 1 – July 31, 2026
**Report Date:** August 1, 2026

---

## 1. Executive Summary

[ynETHx](https://app.yieldnest.finance/token/ynETHx) is YieldNest's MAX product deployed on Ethereum Chain. It auto-compounds ETH yield through DeFi-native strategies, offering liquid exposure and ETH L1 settlement.

_Return accrues as the value of ynETHx increases relative to ETH._

---

## 2. Vault Overview Report (as of August 1, 2026)

### Monthly Overview Report

- Vault TVL: $7,765,354.36 (4,167.66 WETH)
- APY stats from July:
    - 2026-07-24 - 2026-07-31: 5.38%
    - 2026-07-01 - 2026-07-31: 5.41%

---

## 3. Strategy Breakdown (as of August 1, 2026)

| Asset / Strategy | Allocation | Protocol | Description |
| --- | --- | --- | --- |
| wstETH / ynRWAx | 90.00% | AAVE | Supply wstETH on Aave, borrow USD to deposit into ynRWAx. |
| ETH Arbitrage | 9.60% | YieldNest | Delta Neutral Arbitrage Strategy compounding rewards in ETH. |
| WETH | 0.30% | - | Freshly deposited wETH ready to be deployed into strategies. |
| wstETH | 0.09% | Lido | Lido wrapped staked ETH |

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
