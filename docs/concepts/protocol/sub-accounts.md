---
id: sub-accounts
title: Sub Accounts
sidebar_position: 4
---

**Interest Fees**: Morphine charges a 30% platform fee from borrower interest, allocated as follows:

- 50% to 100% is supplied and ready to be burned in case of pool loss. This provides an additional layer of security for lenders, ensuring that the pool remains resilient even during market downturns.
- Up to 50% may be transferred to products built on top of Morphine (e.g., Vaults). This fosters innovation and encourages the development of new DeFi products that leverage Morphine.

**Liquidation Fees**: The prime size depends on the pool parameter, currently set at 3%. Out of this, 1/3 is sent to the insurance fund, while the remaining 2/3 goes to the liquidator. This structure fairly compensates liquidators for their risk and effort while maintaining a healthy insurance fund to protect lenders from potential losses.

**Rebalancing Fees**: The prime size depends on the concerned sub-account. 1/3 is sent to the insurance fund, and the remaining 2/3 goes to the rebalancer. This fee distribution strikes a balance between incentivizing takers to ensure borrowers sub-account rebalancing is completed, and maintaining an adequately funded insurance fund to cover any potential risks.