# YieldNest Monthly Report – ynETHx (March 2026)

![](https://raw.githubusercontent.com/yieldnest/Publications/refs/heads/main/assets/ynETHx/report.png)

---

**Vault Asset**: ynETHx
**Vault Chain**: Ethereum Chain
**Vault Type**: MAX
**Vault Launch Date**: November 2024
**Period Covered:** March 1 – March 31, 2026
**Report Date:** April 1, 2026

---

## 1. Executive Summary

[ynETHx](https://app.yieldnest.finance/token/ynETHx) is YieldNest's MAX product deployed on Ethereum Chain. It auto-compounds ETH yield through DeFi-native strategies, offering liquid exposure and ETH L1 settlement.

_Return accrues as the value of ynETHx increases relative to ETH._

---

## 2. Vault Overview Report (as of April 1, 2026)

### Monthly Overview Report

- Vault TVL: $10,035,685.39 (4,771.6 WETH)
- APY stats from March:
    - 2026-03-24 - 2026-03-31: 4.89%
    - 2026-03-01 - 2026-03-31: 4.27%

---

## 3. Strategy Breakdown (as of April 1, 2026)

| Asset / Strategy | Allocation | Protocol | Description |
| --- | --- | --- | --- |
| wstETH / ynRWAx | 75.33% | AAVE | Supply wstETH on Aave, borrow USD to deposit into ynRWAx. |
| ETH Arbitrage | 17.19% | YieldNest | Delta Neutral Arbitrage Strategy compounding rewards in ETH. |
| ETH Lending | 4.14% | Morpho | Earns rewards by lending ETH to the MEV Capital wETH vault on Morpho while supporting instant withdrawals for ynETHx. |
| WETH | 2.10% | - | Freshly deposited wETH ready to be deployed into strategies. |
| ynETH | 1.24% | YieldNest | A native liquid staking token that earns rewards from ETH validators and AVSs on EigenLayer. |

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

- ✅ [ynRWAx/USDC Now Live on Contango](https://x.com/YieldNestFi/status/2037755012127117340)
- ✅ [YieldNest Launches First Onchain Credit Facility for RWA Liquidity with Cap Protocol & Agra](https://x.com/YieldNestFi/status/2037180864875168073)

## 6. Outlook & Strategy Notes

- Optimized reward collection to improve yield efficiency and auto-compounding
