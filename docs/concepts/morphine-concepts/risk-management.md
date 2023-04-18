---
id: risk-management
title: Risk Management
sidebar_position: 2
---


Lenders face the risk of borrower default, which may result in the loss of their supplied assets. Additionally, there may be smart contract vulnerabilities or exploits that could lead to loss of funds.


## Incentivized exposure

Diversifying the exposure of the pool is crucial, especially in the context of young chains with low liquidity.

A diversified pool reduces the overall risk for lenders, as it prevents an excessive concentration of a single token, which could lead to significant losses if that token's value declines rapidly.

Morphine tackles this problem by:

1. **Pool exposure limit**: Morphine sets a cap on the concentration of any single token in the pool, reducing the overall risk for lenders and ensuring diversification. 

2. **Borrow rate booster**: Morphine introduces a mechanism that increases the borrow rate for borrowers using potentially riskier assets (e.g., staked tokens) as collateral. This compensates lenders for the additional risk they assume and incentivizes borrowers to use a wider range of collateral types. This boost is related to a risk factor,set by the governance (will be then automatic, taking the risk factor from on-chain data feed).

## One-shot liquidation

Morphine offers two flexible liquidation options:

1. **Refund unhealthy sub-account**: A liquidator repays the borrower's debt, and receive excessive collateral.
2. **Flash loan and swap**: A liquidator flash loans the unhealthy sub-account, swaps assets into the debt token, and then refunds the borrower's account, without spending any assets.

Morphine adopts a one-shot liquidation with flat tax fees for these reasons:

- **Speed**: Ensures rapid execution, maintaining platform stability and addressing undercollateralized positions caused by high leverage (up to 15x buying power) and market volatility.
- **Simplicity**: A single transaction reduces complexity for users and developers, streamlining the liquidation process and smart contract implementation.
- **Transparency**: A flat tax fee as the liquidation premium offers clear cost information, helping users make informed risk management decisions.
- **Incentivized liquidators**: The fixed liquidation premium attracts liquidators, ensuring undercollateralized positions are promptly resolved.

The one-shot liquidation, although it may seem unfair at first, is necessary for Morphine's design to ensure platform stability and manage undercollateralized positions effectively. However, to protect borrowers from the potential impact of flat tax liquidation fees, we encourage them to set up a liquidation protector automation.

## Insurance fund

Platform fees collected by Morphine are converted into pool tokens and reserved for potential burning in case of pool loss. This provides an additional layer of security for lenders and contributes to deeper liquidity within the platform.


## Protocols integration

Morphine interacts with other DeFi protocols using adapter smart contracts, which create a standardized interface for seamless integration and modularity while maintaining compatibility with different platforms.

While the platform aims to provide users with a wide range of possibilities by integrating various DeFi protocols, to ensure the security and safety of users' assets, Morphine requires that all integrated contracts undergo thorough auditing by reputable security firms. 


## Data Feed 

We are using Pragma for providing reliable and transparent datafeeds:  
- Token Pricing (calculate collateral value)
- Volatility (liquidation threshold)
- Yield strategies risk metrics (risk factor)