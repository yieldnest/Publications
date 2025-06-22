# YieldNest Monthly Report – ynBNBx (May 2025)

![](https://gov.yieldnest.finance/uploads/default/optimized/1X/72a7e7c3cfd3c29e1546e3e5c638d4350b13b19d_2_690x388.jpeg)

---

**Vault Asset**: ynBNBx
**Vault Chain**: BNB Chain
**Vault Type**: MAX
**Vault Launch Date**: December 2024
**Period Covered:** May 1 – June 1, 2025
**Report Date:** June 11, 2025

---

## 1. Executive Summary

[ynBNBx](https://app.yieldnest.finance/restake/ynBNBx) is YieldNest’s MAX product deployed on BNB Chain. It auto-compounds BNB-linked yield through Binance-integrated and DeFi-native strategies, offering liquid exposure and BNB L1 settlement.

*Rewards accrue as the value of ynBNBx increases relative to BNB.*

---

## 2. Vault Performance Metric (as of June 11, 2025)

| Metric                      | Value                           |
| ------------------------- | ------------------------------- |
| **Gross Yield Generated** | +12.95 BNB                     |
| **Average APY (Est.)**    | 10.79% (annualized)             |
| **TVL (Current)**         | ~22,379.81 BNB ($14.6M USD) |
| **Buffer Allocation**     | ~20.33%                        |
| **Point Eligibility** | Kernel, Astherus                |

---

## 3. Strategy Composition (as of June 11, 2025)

| **Asset**     | **Allocation (%)** | **Yield Source**               | **Description**                                                                                                                                 |
| ------------- | ------------------ | ------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| **ynClisBNB** | 62.61%             | Binance Airdrops               | 	Earns Launchpool, Megadrop & HODLer rewards                       |
| **ynWBNBk**   | 20.33%             | Buffer / Kernel      | Non-yielding wBNB in Kernel for liquidity |
| **ynAsBNBk**  | 15.20%             | Kernel + Launchpool    | Stakes asBNB to earn Kernel & Binance points                                                         |
| **wBNB**      | 1.86%              | Reserve             | Pending capital for deployment                                                                               |
| **slisBNB**   | 0.00%              | Lista DAO | Forms base layer for ynClisBNB                         |

> Vault maintains over 20% liquidity buffer for instant withdrawals while maximizing yield on remaining assets.

---

## 4. Yield Attribution: Airdrops & Incentives (as of June 11, 2025)

| Program                | Token | Airdrop Date | Reward (BNB) | Notes                                      |
| ---------------------- | ----- | ------------ | ------------ | ------------------------------------------ |
| Binance Launchpool     | HUMA   | May 26, 2025 | 12.95 BNB     | -               |

→ **Total Airdrop Yield (BNB)**: 12.95 BNB

---

## 5. Security & Risk Monitoring

Audited Completed:

* [Zokyo - Dec 2024	](https://github.com/yieldnest/Publications/blob/main/audits/zokyo_audit_yieldnest_dec12th_2024.pdf)
* [Composable Security - Jan 2025](https://github.com/yieldnest/Publications/blob/main/audits/composable_security_yieldnest_jan_2025.pdf)
* [Llamarisk - Jan 2025](https://www.llamarisk.com/research/asset-risk-ynbnbx)
* [NFR Audits Feb 2025	](https://github.com/yieldnest/Publications/blob/main/audits/yieldnest_max_vault_withdrawer_audit_report.pdf)

On-Chain Protections:
* ERC-4626 modular vaults
* Strategy whitelisting via Guard Engine
* Proxy upgrade system
* 24/7 monitoring via Hypernative
* Bounded execution for slashing/misallocation defense

---

## 6. Notable Events This Month

* ✅ [YieldNest crossed $500M protocol-wide TVL](https://x.com/YieldNestFi/status/1925240021961093397)

---

## 7. Outlook & Strategy Notes

* Evaluate upcoming Binance Megadrops for early inclusion
* Maintain 20%+ liquidity buffer to support sclaing instant redemption
* Upgrade liquidity buffer to support the Euler ynBNBx vault