---
id: uniswap-protocol
title: Morphine Protocol
sidebar_position: 2
---


Morphine is a non-custodial, permissionless, undercollateralized money market protocol on Starknet that empowers users in their DeFi journey by providing low-risk, attractive APY lending opportunities and a comprehensive toolkit for position management. With features like composable leverage, automation, and seamless integration across a range of DeFi products, Morphine ensures a CEX user-friendly experience while upholding the highest standards of security and transparency in the space.

A first version has been released on Testnet goerli 2.


## How Morphine is built different

|  | Perpetual (DYDX) | Money Market (Compound) | Morphine |
|-----------|-----------|-----------|-----------|
| Buying Power   | 1-30x   | 1-3x   | 1-15x   |
| Borrow cost   | Funding rates   | interest rate  | yield generated - interest rate   |
| Data Feed   | Chainlink   | Chainlink   | Pragma   |
| Collateral in use   | limited   | limited   | UNI V2-V3 LP, 4626, LSDs  |
| Management tools   | limits order: limited, not fully decentralized   | none   | Fully composable automations, permisionless task execution for a prime|
| Interoperability  | None  | Complicated: require Instadapp like services  | Connected to the whole DeFi ecosystem through adapaters |
| Multi-Borrow   | Yes  | Yes | No, pools are isolated   |

## Why Starknet ? 

Morphine is built on Starknet, a ZK-rollup over Ethereum, for several key reasons that contribute to its overall functionality, efficiency, and security:

### Scalability

ZK-rollups like Starknet significantly increase the transaction throughput by bundling multiple transactions into a single proof, which is then posted on the Ethereum blockchain. The lower costs associated with Morphine's use of Starknet makes liquidation and bot execution cheaper ensuring a wider range of users can access financial products, reflecting our commitment to promoting equality and inclusivity within the DeFi space.

### Security

Starknet inherits the security of the Ethereum blockchain while also leveraging zero-knowledge proofs to ensure the privacy and confidentiality of transactions. This helps protect user data and maintain a high level of security within the Morphine platform.

### Vision

Starknet is aligns with Ethereum's philosophy and vision for a decentralized future. As pioneers in the industry, both Starknet and Ethereum have robust and supportive communities that contribute to the growth of a thriving DeFi ecosystem. By choosing Starknet, Morphine actively supports and participates in this vibrant ecosystem, benefiting from its innovative developments and collaborative spirit.

### Account abstraction

StarkNet's account abstraction is a feature that simplifies and enhances the user experience in crypto, Gaming and DeFi applications. Account abstraction allows users to interact with various DeFi applications without having to manage multiple addresses and private keys. This simplification can make Morphine more accessible and user-friendly, particularly for users who are new to the DeFi space.


### Yield opportunities

Starknet is a young Chain , many DeFi applications have been created and came out with a Liquidiy Mining program to incentives users.  Morphine will allow you to get leverage on it.
