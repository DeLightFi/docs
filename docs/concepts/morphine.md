---
id: morphine
title: Morphine 
sidebar_position: 2
---


Morphine is a non-custodial, permissionless, undercollateralized money market protocol on Starknet that empowers users in their DeFi journey by providing low-risk, attractive APY lending opportunities and a comprehensive toolkit for active management. With features like composable leverage, composable automation, and seamless integration across a range of DeFi products, Morphine seamlessly integrates the advantages of both centralized exchanges and DeFi, providing an intuitive, user-friendly experience while harnessing the full potential of decentralized finance.

A first version has been released on Testnet goerli 2.


## How Morphine is built different

Perpetual DEX platforms provide a good user experience for trading assets; however, these assets do not generate yield in DeFi while the long or short positions are active. In contrast, Morphine allows assets to work in DeFi and generate yields even when users take leveraged positions. Additionally, while perpetual DEX platforms rely on funding rates to balance the market between long and short positions, Morphine uses a borrow rate mechanism, which dynamically adjusts interest rates based on supply and demand. This enables a more balanced and efficient market, benefiting both lenders and borrowers in the DeFi ecosystem.

The protocol also differs significantly from traditional overcollateralized loan protocols. In Morphine, assets and collateral are sent to a sub-account with limited access, and only one token can be borrowed. In contrast, other platforms allow users to receive borrowed tokens directly, tokenize the debt, and enable borrowing multiple tokens simultaneously.


|  | Perpetual (DYDX, GMX) | Money Market (Compound, AAVE) | Morphine |
|-----------|-----------|-----------|-----------|
| Buying Power   | 1-30x   | 1-3x   | 1-15x   |
| Borrow cost   | Funding rates   | interest rate  | yield generated - interest rate   |
| Data Feed   | Chainlink   | Chainlink   | Pragma   |
| Collateral in use   | limited   | limited   | ERC20-LP, 4626, LSDs  |
| Management tools   | limits order: limited, not fully decentralized   | none   | Fully composable automations, permisionless task execution for a prime|
| Interoperability  | None  | Complicated: require Instadapp like services  | Connected to the whole DeFi ecosystem through adapaters |
| Multi-Borrow   | Yes  | Yes | No, pools are isolated   |

## Why Starknet ? 

We are building DeFi on Starknet because it offers unparalleled scalability, low transaction costs, and strong security guarantees inherited from Ethereum. Its unique Cairo execution environment enables innovative smart contract functionality, and the rapidly growing ecosystem attracts top-tier talent and investment, ensuring a thriving DeFi future on Starknet.

### Scalability

ZK-rollups like Starknet significantly increase the transaction throughput by bundling multiple transactions into a single proof, which is then posted on the Ethereum blockchain. The lower costs associated with Morphine's use of Starknet makes liquidation and bot execution cheaper ensuring a wider range of users can access financial products, reflecting our commitment to promoting equality and inclusivity within the DeFi space.

### Security

Starknet inherits the security of the Ethereum blockchain while also leveraging zero-knowledge proofs to ensure the privacy and confidentiality of transactions. This helps protect user data and maintain a high level of security within the Morphine platform.

### Vision

Starknet is aligns with Ethereum's philosophy  is the le for a decentralized future. By choosing Starknet, Morphine actively supports and participates in this vibrant ecosystem, benefiting from its innovative developments and collaborative spirit.

### Account abstraction

StarkNet's account abstraction is a feature that simplifies and enhances the user experience in crypto, Gaming and DeFi applications. Account abstraction allows users to interact with various DeFi applications without having to manage multiple addresses and private keys. This simplification can make Morphine more accessible and user-friendly, particularly for users who are new to the DeFi space.


### Yield opportunities

Starknet is a young Chain , many DeFi applications have been created and came out with a Liquidiy Mining program to incentives users.  Morphine will allow you to get leverage on it.
