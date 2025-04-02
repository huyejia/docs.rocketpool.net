---
permalink: /overview/contracts-integrations
---

# 🤝 Contracts & Integrations

Do you love RPL and rETH? Us too! So we put together a list of integrations and services, as well as official contract deployments, to help you discover new places these assets can be used!

If you would like to contribute by helping integrate Rocket Pool into more services and protocols, reach out on [Discord](https://discord.gg/MYrazaZZC4)!

## Key Protocol Contracts

| Chain     | Contract | Address                                                                                                                       |
|-----------|----------|-------------------------------------------------------------------------------------------------------------------------------|
| Mainnet   | Deposit  | [0xDD3f50F8A6CafbE9b31a427582963f465E745AF8](https://etherscan.io/address/0xDD3f50F8A6CafbE9b31a427582963f465E745AF8)         |
| &nbsp;    | Storage  | [0x1d8f8f00cfa6758d7bE78336684788Fb0ee0Fa46](https://etherscan.io/address/0x1d8f8f00cfa6758d7bE78336684788Fb0ee0Fa46)         |
| Hoodi\* | Deposit  | [0x320f3aAB9405e38b955178BBe75c477dECBA0C27](https://hoodi.etherscan.io/address/0x320f3aAB9405e38b955178BBe75c477dECBA0C27) |
| &nbsp;    | Storage  | [0x594Fb75D3dc2DFa0150Ad03F99F97817747dd4E1](https://hoodi.etherscan.io/address/0x594Fb75D3dc2DFa0150Ad03F99F97817747dd4E1) |

Within the protocol, the Storage contract is used to find all the other deployed contract addresses as needed (see this [example](/overview/contracts-usage#interacting-with-rocket-pool)).
See [All Active Deployed Protocol Contracts](#all-active-deployed-protocol-contracts) below for a full list of addresses.

<small>\* Testnet</small>

## Token Contracts

| Chain           | Asset | Address                                                                                                                                                             |
|-----------------|-------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Mainnet         | RPL   | [0xD33526068D116cE69F19A9ee46F0bd304F21A51f](https://etherscan.io/token/0xd33526068d116ce69f19a9ee46f0bd304f21a51f)                                                 |
| &nbsp;          | rETH  | [0xae78736Cd615f374D3085123A210448E74Fc6393](https://etherscan.io/token/0xae78736cd615f374d3085123a210448e74fc6393)                                                 |
| Arbitrum        | RPL   | [0xb766039cc6db368759c1e56b79affe831d0cc507](https://arbiscan.io/token/0xb766039cc6db368759c1e56b79affe831d0cc507)                                                  |
| &nbsp;          | rETH  | [0xec70dcb4a1efa46b8f2d97c310c9c4790ba5ffa8](https://arbiscan.io/token/0xec70dcb4a1efa46b8f2d97c310c9c4790ba5ffa8)                                                  |
| Optimism        | RPL   | [0xc81d1f0eb955b0c020e5d5b264e1ff72c14d1401](https://optimistic.etherscan.io/token/0xc81d1f0eb955b0c020e5d5b264e1ff72c14d1401)                                      |
| &nbsp;          | rETH  | [0x9bcef72be871e61ed4fbbc7630889bee758eb81d](https://optimistic.etherscan.io/token/0x9bcef72be871e61ed4fbbc7630889bee758eb81d)                                      |
| zkSync Era      | RPL   | [0x1CF8553Da5a75C20cdC33532cb19Ef7E3bFFf5BC](https://explorer.zksync.io/address/0x1CF8553Da5a75C20cdC33532cb19Ef7E3bFFf5BC)                                         |
| &nbsp;          | rETH  | [0x32Fd44bB869620C0EF993754c8a00Be67C464806](https://explorer.zksync.io/address/0x32Fd44bB869620C0EF993754c8a00Be67C464806)                                         |
| Polygon         | RPL   | [0x7205705771547cf79201111b4bd8aaf29467b9ec](https://polygonscan.com/token/https://mainnet.infura.io/v3/730706e87a4a41de9b7b8bd4600a72e30x7205705771547cf79201111b4bd8aaf29467b9ec)                                              |
| &nbsp;          | rETH  | [0x0266F4F08D82372CF0FcbCCc0Ff74309089c74d1](https://polygonscan.com/token/0x0266F4F08D82372CF0FcbCCc0Ff74309089c74d1)                                              |
| Polygon (zkEVM) | RPL   | [0x70d35152fBf63FB312709b11a9Bac87519de0019](https://zkevm.polygonscan.com/address/0x70d35152fBf63FB312709b11a9Bac87519de0019)                                      |
| &nbsp;          | rETH  | [0xb23C20EFcE6e24Acca0Cef9B7B7aA196b84EC942](https://zkevm.polygonscan.com/address/0xb23C20EFcE6e24Acca0Cef9B7B7aA196b84EC942)                                      |
| Hoodi\*       | RPL   | [0x1Cc9cF5586522c6F483E84A19c3C2B0B6d027bF0](https://hoodi.etherscan.io/address/0x1Cc9cF5586522c6F483E84A19c3C2B0B6d027bF0)                                       |
| &nbsp;          | rETH  | [0x7322c24752f79c05FFD1E2a6FCB97020C1C264F1](https://hoodi.etherscan.io/address/0x7322c24752f79c05FFD1E2a6FCB97020C1C264F1)                                       |
| Base            | RPL   | [0x1f73EAf55d696BFFA9b0EA16fa987B93b0f4d302](https://basescan.org/address/0x1f73EAf55d696BFFA9b0EA16fa987B93b0f4d302)                                               |
| &nbsp;          | rETH  | [0xB6fe221Fe9EeF5aBa221c348bA20A1Bf5e73624c](https://basescan.org/address/0xB6fe221Fe9EeF5aBa221c348bA20A1Bf5e73624c)                                               |
| Scroll          | rETH  | [0x53878B874283351D26d206FA512aEcE1Bef6C0dD](https://scrollscan.com/address/0x53878b874283351d26d206fa512aece1bef6c0dd)                                             |
| Starknet        | rETH  | [0x0319111a5037cbec2b3e638cc34a3474e2d2608299f3e62866e9cc683208c610](https://starkscan.co/token/0x0319111a5037cbec2b3e638cc34a3474e2d2608299f3e62866e9cc683208c610) |

<small>\* Testnet</small>

## Deposit Pool Contract Version History

| Chain     | RP Version      | Address                                                                                                                       |
|-----------|-----------------|-------------------------------------------------------------------------------------------------------------------------------|
| Mainnet   | v1.2 (Atlas)    | [0xDD3f50F8A6CafbE9b31a427582963f465E745AF8](https://e`therscan.io/address/0xDD3f50F8A6CafbE9b31a427582963f465E745AF8)        |
| &nbsp;    | v1.1 (Redstone) | [0x2cac916b2A963Bf162f076C0a8a4a8200BCFBfb4](https://etherscan.io/address/0x2cac916b2A963Bf162f076C0a8a4a8200BCFBfb4)         |
| &nbsp;    | v1.0            | [0x4D05E3d48a938db4b7a9A59A802D5b45011BDe58](https://etherscan.io/address/0x4D05E3d48a938db4b7a9A59A802D5b45011BDe58)         |

<small>\* Testnet</small>

## Integrations

| Category         | Service                       | Link                                                                                                                                                                                                                           | Link                                                                                                                                                                        |
|------------------|-------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Exchanges        | 1inch (Mainnet)               | -                                                                                                                                                                                                                              | [ETH/rETH](https://app.1inch.io/#/1/simple/swap/1:ETH/1:rETH)                                                                                                               |
| &nbsp;           | Balancer (Mainnet)            | [RPL Pools](https://balancer.fi/pools?skip=0&textSearch=rpl)                                                                                                                                                                   | [rETH Pools](https://balancer.fi/pools?skip=0&textSearch=reth)                                                                                                              |
| &nbsp;           | Curve (Mainnet)               | -                                                                                                                                                                                                                              | [rETH](https://curve.fi/dex/#/ethereum/pools?search=rETH)                                                                                                                   |
| &nbsp;           | CowSwap (Mainnet)             | [ETH/RPL](https://swap.cow.fi/#/1/swap/ETH/RPL)                                                                                                                                                                                | [ETH/rETH](https://swap.cow.fi/#/1/swap/ETH/rETH)                                                                                                                           |
| &nbsp;           | Hop (Multichain)              | [ETH/RPL](https://app.hop.exchange)                                                                                                                                                                                 | [ETH/rETH](https://app.hop.exchange)                                                                                                                            |
| &nbsp;           | ShapeShift (Multichain)       | [ETH/RPL](https://app.shapeshift.com/)                                                                                                                                                                                         | [ETH/rETH](https://app.shapeshift.com/)                                                                                                                                     |
| &nbsp;           | PancakeSwap (Multichain)      | [Pools](https://pancakeswap.finance/liquidity/pools?chain=eth&token=1%3A0xae78736Cd615f374D3085123A210448E74Fc6393&token=324%3A0x32Fd44bB869620C0EF993754c8a00Be67C464806&token=1%3A0xD33526068D116cE69F19A9ee46F0bd304F21A51f) | [wETH/rETH](https://pancakeswap.finance/liquidity/pool/eth/0x2201d2400d30BFD8172104B4ad046d019CA4E7bd)                                                                      |
| &nbsp;           | Uniswap (Mainnet)             | [ETH/RPL](https://app.uniswap.org/#/swap?inputCurrency=ETH&outputCurrency=0xd33526068d116ce69f19a9ee46f0bd304f21a51f&chainId=1)                                                                                                | [ETH/rETH](https://app.uniswap.org/#/swap?inputCurrency=ETH&outputCurrency=0xae78736Cd615f374D3085123A210448E74Fc6393&chainId=1)                                            |
| &nbsp;           | Uniswap (Arbitrum)            | [ETH/RPL](https://app.uniswap.org/#/swap?inputCurrency=ETH&outputCurrency=0xb766039cc6db368759c1e56b79affe831d0cc507&chain=arbitrum)                                                                                           | [ETH/rETH](https://app.uniswap.org/#/swap?inputCurrency=ETH&outputCurrency=0xec70dcb4a1efa46b8f2d97c310c9c4790ba5ffa8&chain=arbitrum)                                       |
| &nbsp;           | Uniswap (Optimism)            | -                                                                                                                                                                                                                              | [ETH/rETH](https://app.uniswap.org/#/swap?inputCurrency=ETH&outputCurrency=0x9bcef72be871e61ed4fbbc7630889bee758eb81d&chain=optimism)                                       |
| &nbsp;           | Uniswap (Polygon)             | -                                                                                                                                                                                                                              | [wETH/rETH](https://app.uniswap.org/#/swap?inputCurrency=0x7ceB23fD6bC0adD59E62ac25578270cFf1b9f619&outputCurrency=0x0266F4F08D82372CF0FcbCCc0Ff74309089c74d1&chain=polygon) |
| Lending          | Aave                          | -                                                                                                                                                                                                                              | [Aave](https://app.aave.com)                                                                                                                                                |
| &nbsp;           | Compound                      | -                                                                                                                                                                                                                              | [Compound](https://app.compound.finance)                                                                                                                                    |
| &nbsp;           | Morpho                        | -                                                                                                                                                                                                                              | [Morpho](https://app.morpho.org)                                                                                                                                            |
| &nbsp;           | Euler Finance                 | -                                                                                                                                                                                                                              | [Euler Finance](https://app.euler.finance)                                                                                                                                  |
| &nbsp;           | Moonwell                      | -                                                                                                                                                                                                                              | [Moonwell](https://moonwell.fi/discover)                                                                                                                                    |
| &nbsp;           | Spark                         | -                                                                                                                                                                                                                              | [Spark](https://app.spark.fi)                                                                                                                                               |
| &nbsp;           | Silo                          | -                                                                                                                                                                                                                              | [Silo](https://app.silo.finance)                                                                                                                                            |
| &nbsp;           | Alchemix                      | -                                                                                                                                                                                                                              | [Alchemix](https://alchemix.fi/vaults)                                                                                                                                      |
| &nbsp;           | MYSO Finance                  | -                                                                                                                                                                                                                              | [MYSO Finance](https://app.myso.finance/)                                                                                                                                   |
| Oracles (NAV)    | RP oDAO Rate (Mainnet)        | -                                                                                                                                                                                                                              | [rETH/ETH](https://etherscan.io/address/0xae78736cd615f374d3085123a210448e74fc6393#readContract#F6)                                                                         |
| &nbsp;           | RP Rate Provider (Optimism)   | -                                                                                                                                                                                                                              | [rETH/ETH](https://github.com/rocket-pool/rocketpool-ovm-oracle)                                                                                                            |
| &nbsp;           | RP Rate Provider (Arbitrum)   | -                                                                                                                                                                                                                              | [rETH/ETH](https://github.com/rocket-pool/rocketpool-arbitrum-oracle)                                                                                                       |
| &nbsp;           | RP Rate Provider (Polygon)    | -                                                                                                                                                                                                                              | [rETH/ETH](https://github.com/rocket-pool/rocketpool-polygon-oracle)                                                                                                        |
| &nbsp;           | RP Rate Provider (zksync era) | -                                                                                                                                                                                                                              | [rETH/ETH](https://github.com/rocket-pool/rocketpool-zksync-oracle)                                                                                                         |
| &nbsp;           | Chainlink (Arbitrum)          | -                                                                                                                                                                                                                              | [rETH/ETH](https://data.chain.link/arbitrum/mainnet/crypto-eth/reth-eth-exchange-rate)                                                                                      |
| Oracles (Market) | RP oDAO Rate (Mainnet)        | [ETH/RPL](https://etherscan.io/address/0x751826b107672360b764327631cC5764515fFC37#readContract#F3)                                                                                                                             | -                                                                                                                                                                           |
| &nbsp;           | Chainlink (Mainnet)           | -                                                                                                                                                                                                                              | [rETH/ETH](https://data.chain.link/ethereum/mainnet/crypto-eth/reth-eth)                                                                                                    |
| &nbsp;           | Maker (Mainnet)               | -                                                                                                                                                                                                                              | [rETH/USD](https://etherscan.io/address/0xee7f0b350aa119b3d05dc733a4621a81972f7d47)                                                                                         |
| Trackers         | DefiLlama                     | [RPL](https://defillama.com/protocol/rocket-pool)                                                                                                                                                                              | -                                                                                                                                                                           |
| &nbsp;           | Delta                         | -                                                                                                                                                                                                                              | [rETH](https://delta.app/)                                                                                                                                                  |
| &nbsp;           | RocketScan                    | [RPL](https://rocketscan.io/rpl)                                                                                                                                                                                               | [rETH](https://rocketscan.io/reth)                                                                                                                                          |
| &nbsp;           | iYield                        | [RPL](https://go.iyield.com/rp)                                                                                                                                                                                                | [rETH](https://go.iyield.com/rp)                                                                                                                                           |
| Vaults           | Aura Finance                  | -                                                                                                                                                                                                                              | [Aura](https://app.aura.finance/#/)                                                                                                                                         |
| &nbsp;           | Gamma                         | -                                                                                                                                                                                                                              | [Gamma](https://app.gamma.xyz/vault/uni/ethereum/details/reth-weth-500-pegged-price)                                                                                        |
| &nbsp;           | Notional Finance              | -                                                                                                                                                                                                                              | [Notional Finance](https://notional.finance)                                                                                                                                |
| &nbsp;           | Contango                      | -                                                                                                                                                                                                                              | [Contango](https://app.contango.xyz)                                                                                                                                        |
| &nbsp;           | Flat Money                    | -                                                                                                                                                                                                                              | [Flat Money](https://flat.money)                                                                                                                                            |


## Management Committee Wallets

| Chain    | Committee | Address                                                                                                                         |
|----------|-----------|---------------------------------------------------------------------------------------------------------------------------------|
| Mainnet  | GMC       | [0x6efD08303F42EDb68F2D6464BCdCA0824e1C813a](https://app.safe.global/home?safe=eth:0x6efD08303F42EDb68F2D6464BCdCA0824e1C813a)  |
| &nbsp;   | IMC       | [0xb867EA3bBC909954d737019FEf5AB25dFDb38CB9](https://app.safe.global/home?safe=eth:0xb867EA3bBC909954d737019FEf5AB25dFDb38CB9)  |
| Arbitrum | IMC       | [0xd7102A3744c302f167c53621453516345bC460d7](https://app.safe.global/home?safe=arb1:0xd7102A3744c302f167c53621453516345bC460d7) |

## All Active Deployed Protocol Contracts

| Chain   | Contract Name                         | Address                                                                                                                       |
|---------|---------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|
| Mainnet | addressQueueStorage                   | [0x44E31944E1A6F3b8F805E105B130F8bdb7E2EBd8](https://etherscan.io/address/0x44E31944E1A6F3b8F805E105B130F8bdb7E2EBd8)         |
| &nbsp;  | addressSetStorage                     | [0xD4ae2511dF21F367792bA4D67c6eb032171c6a16](https://etherscan.io/address/0xD4ae2511dF21F367792bA4D67c6eb032171c6a16)         |
| &nbsp;  | rocketAuctionManager                  | [0x1a2F00D187C9388fDa3Bf2dc46a6b4740849EcCE](https://etherscan.io/address/0x1a2F00D187C9388fDa3Bf2dc46a6b4740849EcCE)         |
| &nbsp;  | rocketClaimDAO                        | [0xFe6Db0ce3F61a4aE04c0A3E62F775a6f511C9aaC](https://etherscan.io/address/0xFe6Db0ce3F61a4aE04c0A3E62F775a6f511C9aaC)         |
| &nbsp;  | rocketDAONodeTrusted                  | [0xb8e783882b11Ff4f6Cef3C501EA0f4b960152cc9](https://etherscan.io/address/0xb8e783882b11Ff4f6Cef3C501EA0f4b960152cc9)         |
| &nbsp;  | rocketDAONodeTrustedActions           | [0x029d946F28F93399a5b0D09c879FC8c94E596AEb](https://etherscan.io/address/0x029d946F28F93399a5b0D09c879FC8c94E596AEb)         |
| &nbsp;  | rocketDAONodeTrustedProposals         | [0xb0ec3F657ef43A615aB480FA8D5A53BF2c2f05d5](https://etherscan.io/address/0xb0ec3F657ef43A615aB480FA8D5A53BF2c2f05d5)         |
| &nbsp;  | rocketDAONodeTrustedSettingsMembers   | [0xdA1AB39e62E0A5297AF44C7064E501b0613f0D01](https://etherscan.io/address/0xdA1AB39e62E0A5297AF44C7064E501b0613f0D01)         |
| &nbsp;  | rocketDAONodeTrustedSettingsMinipool  | [0xE535fA45e12d748393C117C6D8EEBe1a7D124d95](https://etherscan.io/address/0xE535fA45e12d748393C117C6D8EEBe1a7D124d95)         |
| &nbsp;  | rocketDAONodeTrustedSettingsProposals | [0xAD038f8994a6bd51C8A72D3721CEd83401D4d2b0](https://etherscan.io/address/0xAD038f8994a6bd51C8A72D3721CEd83401D4d2b0)         |
| &nbsp;  | rocketDAONodeTrustedSettingsRewards   | [0x7322c24752f79c05FFD1E2a6FCB97020C1C264F1](https://etherscan.io/address/0x7322c24752f79c05FFD1E2a6FCB97020C1C264F1)         |
| &nbsp;  | rocketDAONodeTrustedUpgrade           | [0x952999Ec97248547D810Fd6464fDb78855b022aB](https://etherscan.io/address/0x952999Ec97248547D810Fd6464fDb78855b022aB)         |
| &nbsp;  | rocketDAOProposal                     | [0x1e94e6131Ba5B4F193d2A1067517136C52ddF102](https://etherscan.io/address/0x1e94e6131Ba5B4F193d2A1067517136C52ddF102)         |
| &nbsp;  | rocketDAOProtocol                     | [0x1b714ed0ce30A8BeDC5b4253DaAa08c84CA5BFcb](https://etherscan.io/address/0x1b714ed0ce30A8BeDC5b4253DaAa08c84CA5BFcb)         |
| &nbsp;  | rocketDAOProtocolActions              | [0xB50d513de40eE70A662c39207b4382a693f9e08D](https://etherscan.io/address/0xB50d513de40eE70A662c39207b4382a693f9e08D)         |
| &nbsp;  | rocketDAOProtocolProposals            | [0x6D736da1dC2562DBeA9998385A0A27d8c2B2793e](https://etherscan.io/address/0x6D736da1dC2562DBeA9998385A0A27d8c2B2793e)         |
| &nbsp;  | rocketDAOProtocolProposal             | [0x2D627A50Dc1C4EDa73E42858E8460b0eCF300b25](https://etherscan.io/address/0x2D627A50Dc1C4EDa73E42858E8460b0eCF300b25)         |
| &nbsp;  | rocketDAOProtocolSettingsAuction      | [0x364F989A3C9a1F66cB51b9043680974eA08C0d18](https://etherscan.io/address/0x364F989A3C9a1F66cB51b9043680974eA08C0d18)         |
| &nbsp;  | rocketDAOProtocolSettingsDeposit      | [0xD846AA34caEf083DC4797d75096F60b6E08B7418](https://etherscan.io/address/0xD846AA34caEf083DC4797d75096F60b6E08B7418)         |
| &nbsp;  | rocketDAOProtocolSettingsInflation    | [0x1d4AAEaE7C8b75a8e5ab589a84516853DBDdd735](https://etherscan.io/address/0x1d4AAEaE7C8b75a8e5ab589a84516853DBDdd735)         |
| &nbsp;  | rocketDAOProtocolSettingsMinipool     | [0xA416A7a07925d60F794E20532bc730749611A220](https://etherscan.io/address/0xA416A7a07925d60F794E20532bc730749611A220)         |
| &nbsp;  | rocketDAOProtocolSettingsNetwork      | [0x89682e5F9bf69C909FC5E21a06495ac35E3671Ab](https://etherscan.io/address/0x89682e5F9bf69C909FC5E21a06495ac35E3671Ab)         |
| &nbsp;  | rocketDAOProtocolSettingsNode         | [0x448DA008c7EB2501165c9Aa62DfFEeC4405bC660](https://etherscan.io/address/0x448DA008c7EB2501165c9Aa62DfFEeC4405bC660)         |
| &nbsp;  | rocketDAOProtocolSettingsRewards      | [0x8857610Ba0A7caFD4dBE1120bfF03E9c74fc4124](https://etherscan.io/address/0x8857610Ba0A7caFD4dBE1120bfF03E9c74fc4124)         |
| &nbsp;  | rocketDepositPool                     | [0xDD3f50F8A6CafbE9b31a427582963f465E745AF8](https://etherscan.io/address/0xDD3f50F8A6CafbE9b31a427582963f465E745AF8)         |
| &nbsp;  | rocketMerkleDistributorMainnet        | [0x5cE71E603B138F7e65029Cc1918C0566ed0dBD4B](https://etherscan.io/address/0x5cE71E603B138F7e65029Cc1918C0566ed0dBD4B)         |
| &nbsp;  | rocketMinipoolBase                    | [0x560656C8947564363497E9C78A8BDEff8d3EFF33](https://etherscan.io/address/0x560656C8947564363497E9C78A8BDEff8d3EFF33)         |
| &nbsp;  | rocketMinipoolBondReducer             | [0xf7aB34C74c02407ed653Ac9128731947187575C0](https://etherscan.io/address/0xf7aB34C74c02407ed653Ac9128731947187575C0)         |
| &nbsp;  | rocketMinipoolDelegate                | [0x03d30466d199Ef540823fe2a22CAE2E3b9343bb0](https://etherscan.io/address/0x03d30466d199Ef540823fe2a22CAE2E3b9343bb0)         |
| &nbsp;  | rocketMinipoolFactory                 | [0x7B8c48256CaF462670f84c7e849cab216922B8D3](https://etherscan.io/address/0x7B8c48256CaF462670f84c7e849cab216922B8D3)         |
| &nbsp;  | rocketMinipoolManager                 | [0xF82991Bd8976c243eB3b7CDDc52AB0Fc8dc1246C](https://etherscan.io/address/0xF82991Bd8976c243eB3b7CDDc52AB0Fc8dc1246C)         |
| &nbsp;  | rocketMinipoolPenalty                 | [0xE64AC47b6e2FEcfCDEA35147Fe61af9894A06ba6](https://etherscan.io/address/0xE64AC47b6e2FEcfCDEA35147Fe61af9894A06ba6)         |
| &nbsp;  | rocketMinipoolQueue                   | [0x9e966733e3E9BFA56aF95f762921859417cF6FaA](https://etherscan.io/address/0x9e966733e3E9BFA56aF95f762921859417cF6FaA)         |
| &nbsp;  | rocketMinipoolStatus                  | [0xa52451b9d25EEf02BE42B3A8161A18f947F8A6a5](https://etherscan.io/address/0xa52451b9d25EEf02BE42B3A8161A18f947F8A6a5)         |
| &nbsp;  | rocketNetworkBalances                 | [0x6Cc65bF618F55ce2433f9D8d827Fc44117D81399](https://etherscan.io/address/0x6Cc65bF618F55ce2433f9D8d827Fc44117D81399)         |
| &nbsp;  | rocketNetworkFees                     | [0xf824e2d69dc7e7c073162C2bdE87dA4746d27a0f](https://etherscan.io/address/0xf824e2d69dc7e7c073162C2bdE87dA4746d27a0f)         |
| &nbsp;  | rocketNetworkPenalties                | [0x9294Fc6F03c64Cc217f5BE8697EA3Ed2De77e2F8](https://etherscan.io/address/0x9294Fc6F03c64Cc217f5BE8697EA3Ed2De77e2F8)         |
| &nbsp;  | rocketNetworkPrices                   | [0x25E54Bf48369b8FB25bB79d3a3Ff7F3BA448E382](https://etherscan.io/address/0x25E54Bf48369b8FB25bB79d3a3Ff7F3BA448E382)         |
| &nbsp;  | rocketNodeDeposit                     | [0x672335B91b4f2096D897cA1B12Ef4ec9346A5ff4](https://etherscan.io/address/0x672335B91b4f2096D897cA1B12Ef4ec9346A5ff4)         |
| &nbsp;  | rocketNodeDistributorDelegate         | [0x32778D6bf5b93B89177D328556EeeB35c09f472b](https://etherscan.io/address/0x32778D6bf5b93B89177D328556EeeB35c09f472b)         |
| &nbsp;  | rocketNodeDistributorFactory          | [0xe228017f77B3E0785e794e4c0a8A6b935bB4037C](https://etherscan.io/address/0xe228017f77B3E0785e794e4c0a8A6b935bB4037C)         |
| &nbsp;  | rocketNodeManager                     | [0x2b52479F6ea009907e46fc43e91064D1b92Fdc86](https://etherscan.io/address/0x2b52479F6ea009907e46fc43e91064D1b92Fdc86)         |
| &nbsp;  | rocketNodeStaking                     | [0xF18Dc176C10Ff6D8b5A17974126D43301F8EEB95](https://etherscan.io/address/0xF18Dc176C10Ff6D8b5A17974126D43301F8EEB95)         |
| &nbsp;  | rocketRewardsPool                     | [0xEE4d2A71cF479e0D3d0c3c2C923dbfEB57E73111](https://etherscan.io/address/0xEE4d2A71cF479e0D3d0c3c2C923dbfEB57E73111)         |
| &nbsp;  | rocketSmoothingPool                   | [0xd4E96eF8eee8678dBFf4d535E033Ed1a4F7605b7](https://etherscan.io/address/0xd4E96eF8eee8678dBFf4d535E033Ed1a4F7605b7)         |
| &nbsp;  | rocketStorage                         | [0x1d8f8f00cfa6758d7bE78336684788Fb0ee0Fa46](https://etherscan.io/address/0x1d8f8f00cfa6758d7bE78336684788Fb0ee0Fa46)         |
| &nbsp;  | rocketTokenRETH                       | [0xae78736Cd615f374D3085123A210448E74Fc6393](https://etherscan.io/address/0xae78736Cd615f374D3085123A210448E74Fc6393)         |
| &nbsp;  | rocketTokenRPL                        | [0xD33526068D116cE69F19A9ee46F0bd304F21A51f](https://etherscan.io/address/0xD33526068D116cE69F19A9ee46F0bd304F21A51f)         |
| &nbsp;  | rocketUpgradeOneDotOne                | [0xC680a22b4F03977f69b51A09f3Dbe922eb77C8FE](https://etherscan.io/address/0xc680a22b4f03977f69b51a09f3dbe922eb77c8fe)         |
| &nbsp;  | rocketUpgradeOneDotTwo                | [0x9a0b5d3101d111EA0edD573d45ef2208CC97984a](https://etherscan.io/address/0x9a0b5d3101d111EA0edD573d45ef2208CC97984a)         |
| &nbsp;  | rocketUpgradeOneDotThree              | [0x5dC69083B68CDb5c9ca492A0A5eC581e529fb73C](https://etherscan.io/address/0x5dC69083B68CDb5c9ca492A0A5eC581e529fb73C)         |
| &nbsp;  | rocketUpgradeOneDotThreeDotOne        | [0xc2C81454427b1E53Fdf5d3B45561e3c18F90f9eD](https://etherscan.io/address/0xc2C81454427b1E53Fdf5d3B45561e3c18F90f9eD)         |
| &nbsp;  | rocketVault                           | [0x3bDC69C4E5e13E52A65f5583c23EFB9636b469d6](https://etherscan.io/address/0x3bDC69C4E5e13E52A65f5583c23EFB9636b469d6)         |
| &nbsp;  | rocketNetworkSnapshots                | [0x7603352f1C4752Ac07AAC94e48632b65FDF1D35c](https://etherscan.io/address/0x7603352f1C4752Ac07AAC94e48632b65FDF1D35c)         |
| &nbsp;  | rocketNetworkVoting                   | [0x77cF0f32BDd06242465eb3318a81196194a13daA](https://etherscan.io/address/0x77cF0f32BDd06242465eb3318a81196194a13daA)         |
| &nbsp;  | rocketDAOProtocolSettingsProposals    | [0x5f24E4a1A1f134a5a6952A9965721E6344898497](https://etherscan.io/address/0x5f24E4a1A1f134a5a6952A9965721E6344898497)         |
| &nbsp;  | rocketDAOProtocolVerifier             | [0xd1f7e573cdC64FC0B201ca37aB50bC7Dd880040A](https://etherscan.io/address/0xd1f7e573cdC64FC0B201ca37aB50bC7Dd880040A)         |
| &nbsp;  | rocketDAOSecurity                     | [0x84aE6D61Df5c6ba7196b5C76Bcb112B8a689aD37](https://etherscan.io/address/0x84aE6D61Df5c6ba7196b5C76Bcb112B8a689aD37)         |
| &nbsp;  | rocketDAOSecurityActions              | [0xeaa442dF4Bb5394c66C8024eFb4979bEc89Eb59a](https://etherscan.io/address/0xeaa442dF4Bb5394c66C8024eFb4979bEc89Eb59a)         |
| &nbsp;  | rocketDAOSecurityProposals            | [0x6004Fa90a27dB9971aDD200d1A3BB34444db9Fb7](https://etherscan.io/address/0x6004Fa90a27dB9971aDD200d1A3BB34444db9Fb7)         |
| &nbsp;  | rocketDAOProtocolSettingsSecurity     | [0x1ec364CDD9697F56B8CB17a745B98C2b862CBE29](https://etherscan.io/address/0x1ec364CDD9697F56B8CB17a745B98C2b862CBE29)         |
| &nbsp;  | rocketDAOProtocolProposal             | [0x2D627A50Dc1C4EDa73E42858E8460b0eCF300b25](https://etherscan.io/address/0x2D627A50Dc1C4EDa73E42858E8460b0eCF300b25)         |
| &nbsp;  | rocketSwapRouter                      | [0x16d5a408e807db8ef7c578279beeee6b228f1c1c](https://etherscan.io/address/0x16d5a408e807db8ef7c578279beeee6b228f1c1c)         |
| Hoodi\* | addressQueueStorage                   | [0x07FCaBCbe4ff0d80c2b1eb42855C0131b6cba2F4](http://hoodi.etherscan.io/address/0x07FCaBCbe4ff0d80c2b1eb42855C0131b6cba2F4) |
| &nbsp;  | addressSetStorage                     | [0xA805d68b61956BC92d556F2bE6d18747adAeEe82](http://hoodi.etherscan.io/address/0xA805d68b61956BC92d556F2bE6d18747adAeEe82) |
| &nbsp;  | rocketAuctionManager                  | [0x84D11B65E026F7aA08F5497dd3593fb083410B71](http://hoodi.etherscan.io/address/0x84D11B65E026F7aA08F5497dd3593fb083410B71) |
| &nbsp;  | rocketClaimDAO                        | [0xC680a22b4F03977f69b51A09f3Dbe922eb77C8FE](http://hoodi.etherscan.io/address/0xC680a22b4F03977f69b51A09f3Dbe922eb77C8FE) |
| &nbsp;  | rocketDAONodeTrusted                  | [0x56CD23Baaf2e7cb7056968d85E5EFe343b0E1DC2](http://hoodi.etherscan.io/address/0x56CD23Baaf2e7cb7056968d85E5EFe343b0E1DC2) |
| &nbsp;  | rocketDAONodeTrustedActions           | [0xa0f327589B08CEB824c21CDe8eaD5a3e6ca9edF7](http://hoodi.etherscan.io/address/0xa0f327589B08CEB824c21CDe8eaD5a3e6ca9edF7) |
| &nbsp;  | rocketDAONodeTrustedProposals         | [0x2d3142a05bDD16a3223B585a7A48132867dA6480](http://hoodi.etherscan.io/address/0x2d3142a05bDD16a3223B585a7A48132867dA6480) |
| &nbsp;  | rocketDAONodeTrustedSettingsMembers   | [0x5c2D33A015D132D4f590f00df807Bb1052531ab9](http://hoodi.etherscan.io/address/0x5c2D33A015D132D4f590f00df807Bb1052531ab9) |
| &nbsp;  | rocketDAONodeTrustedSettingsMinipool  | [0x5ffe8bD3165e80D51ce834B32a6B6C02233494bF](http://hoodi.etherscan.io/address/0x5ffe8bD3165e80D51ce834B32a6B6C02233494bF) |
| &nbsp;  | rocketDAONodeTrustedSettingsProposals | [0xe4C3Ec6A20bE31296032F968cEadeE9e9Aa76535](http://hoodi.etherscan.io/address/0xe4C3Ec6A20bE31296032F968cEadeE9e9Aa76535) |
| &nbsp;  | rocketDAONodeTrustedSettingsRewards   | [0x2FB42FfE2d7dF8381853e96304300c6a5E846905](http://hoodi.etherscan.io/address/0x2FB42FfE2d7dF8381853e96304300c6a5E846905) |
| &nbsp;  | rocketDAONodeTrustedUpgrade           | [0x4640b8610f3eFdeb8d44834ADb3228d0E79eaa09](http://hoodi.etherscan.io/address/0x4640b8610f3eFdeb8d44834ADb3228d0E79eaa09) |
| &nbsp;  | rocketDAOProposal                     | [0xEFfb0c7350F1293a997112b3C2594Cdc34B36F18](http://hoodi.etherscan.io/address/0xEFfb0c7350F1293a997112b3C2594Cdc34B36F18) |
| &nbsp;  | rocketDAOProtocol                     | [0xBD1E62AEbfA1E60797484916685E2B9e62ADbF7B](http://hoodi.etherscan.io/address/0xBD1E62AEbfA1E60797484916685E2B9e62ADbF7B) |
| &nbsp;  | rocketDAOProtocolActions              | [0x1AA4544cE0fd51596B6d51d0f55A40e409B8BAd4](http://hoodi.etherscan.io/address/0x1AA4544cE0fd51596B6d51d0f55A40e409B8BAd4) |
| &nbsp;  | rocketDAOProtocolProposals            | [0x762e79b27feE0C0975f9caBEa9E9976006A7aD98](http://hoodi.etherscan.io/address/0x762e79b27feE0C0975f9caBEa9E9976006A7aD98) |
| &nbsp;  | RocketDAOProtocolProposal             | [0x17Cf2c5d69E4F222bcaDD86d210FE9dc8BadA60B](http://hoodi.etherscan.io/address/0x17Cf2c5d69E4F222bcaDD86d210FE9dc8BadA60B) |
| &nbsp;  | rocketDAOProtocolSettingsAuction      | [0xD9D9202661DE12aaAa478a704eA319B3F24AE711](http://hoodi.etherscan.io/address/0xD9D9202661DE12aaAa478a704eA319B3F24AE711) |
| &nbsp;  | rocketDAOProtocolSettingsDeposit      | [0x47B600D9127a473e45B693A7badD9F4d929d5b76](http://hoodi.etherscan.io/address/0x47B600D9127a473e45B693A7badD9F4d929d5b76) |
| &nbsp;  | rocketDAOProtocolSettingsInflation    | [0xb1029Ac2Be4e08516697093e2AFeC435057f3511](http://hoodi.etherscan.io/address/0xb1029Ac2Be4e08516697093e2AFeC435057f3511) |
| &nbsp;  | rocketDAOProtocolSettingsMinipool     | [0x83B7beA05c2aa38b659847AB21f4039277b8A0B9](http://hoodi.etherscan.io/address/0x83B7beA05c2aa38b659847AB21f4039277b8A0B9) |
| &nbsp;  | rocketDAOProtocolSettingsNetwork      | [0x05330300f829AD3fC8f33838BC88CFC4093baD53](http://hoodi.etherscan.io/address/0x05330300f829AD3fC8f33838BC88CFC4093baD53) |
| &nbsp;  | rocketDAOProtocolSettingsNode         | [0x710E405B60e5dD6c96Cfe926F490c5eDe17d1ECc](http://hoodi.etherscan.io/address/0x710E405B60e5dD6c96Cfe926F490c5eDe17d1ECc) |
| &nbsp;  | rocketDAOProtocolSettingsRewards      | [0x614A5be866A0EC908cA9aE0d7D3eB100492A9f4e](http://hoodi.etherscan.io/address/0x614A5be866A0EC908cA9aE0d7D3eB100492A9f4e) |
| &nbsp;  | rocketDepositPool                     | [0x320f3aAB9405e38b955178BBe75c477dECBA0C27](http://hoodi.etherscan.io/address/0x320f3aAB9405e38b955178BBe75c477dECBA0C27) |
| &nbsp;  | rocketMerkleDistributorMainnet        | [0xfD33e53d0400f52C486B6d1484f1827AD2341405](http://hoodi.etherscan.io/address/0xfD33e53d0400f52C486B6d1484f1827AD2341405) |
| &nbsp;  | rocketMinipoolBase                    | [0xac2245BE4C2C1E9752499Bcd34861B761d62fC27](http://hoodi.etherscan.io/address/0xac2245BE4C2C1E9752499Bcd34861B761d62fC27) |
| &nbsp;  | rocketMinipoolBondReducer             | [0x6d010C43d4e96D74C422f2e27370AF48711B49bF](http://hoodi.etherscan.io/address/0x6d010C43d4e96D74C422f2e27370AF48711B49bF) |
| &nbsp;  | rocketMinipoolDelegate                | [0xddB6E648D6cbeAB31A34a21cA5229db3FF16C9b6](http://hoodi.etherscan.io/address/0xddB6E648D6cbeAB31A34a21cA5229db3FF16C9b6) |
| &nbsp;  | rocketMinipoolFactory                 | [0xDD3f50F8A6CafbE9b31a427582963f465E745AF8](http://hoodi.etherscan.io/address/0xDD3f50F8A6CafbE9b31a427582963f465E745AF8) |
| &nbsp;  | rocketMinipoolManager                 | [0xe228017f77B3E0785e794e4c0a8A6b935bB4037C](http://hoodi.etherscan.io/address/0xe228017f77B3E0785e794e4c0a8A6b935bB4037C) |
| &nbsp;  | rocketMinipoolPenalty                 | [0x54705f80D7C51Fcffd9C659ce3f3C9a7dCCf5788](http://hoodi.etherscan.io/address/0x54705f80D7C51Fcffd9C659ce3f3C9a7dCCf5788) |
| &nbsp;  | rocketMinipoolQueue                   | [0x4220EECD69B2e1e70a7001637cc3D839EE2E97f5](http://hoodi.etherscan.io/address/0x4220EECD69B2e1e70a7001637cc3D839EE2E97f5) |
| &nbsp;  | rocketNetworkBalances                 | [0x9294Fc6F03c64Cc217f5BE8697EA3Ed2De77e2F8](http://hoodi.etherscan.io/address/0x9294Fc6F03c64Cc217f5BE8697EA3Ed2De77e2F8) |
| &nbsp;  | rocketNetworkFees                     | [0x2cac916b2A963Bf162f076C0a8a4a8200BCFBfb4](http://hoodi.etherscan.io/address/0x2cac916b2A963Bf162f076C0a8a4a8200BCFBfb4) |
| &nbsp;  | rocketNetworkPenalties                | [0xCc82C913B9f3a207b332d216B101970E39E59DB3](http://hoodi.etherscan.io/address/0xCc82C913B9f3a207b332d216B101970E39E59DB3) |
| &nbsp;  | rocketNetworkPrices                   | [0x029d946F28F93399a5b0D09c879FC8c94E596AEb](http://hoodi.etherscan.io/address/0x029d946F28F93399a5b0D09c879FC8c94E596AEb) |
| &nbsp;  | rocketNodeDeposit                     | [0x8e7dcE7C58c13230041f6f51Ca017c6Cc232e938](http://hoodi.etherscan.io/address/0x8e7dcE7C58c13230041f6f51Ca017c6Cc232e938) |
| &nbsp;  | rocketNodeDistributorDelegate         | [0x9e966733e3E9BFA56aF95f762921859417cF6FaA](http://hoodi.etherscan.io/address/0x9e966733e3E9BFA56aF95f762921859417cF6FaA) |
| &nbsp;  | rocketNodeDistributorFactory          | [0x42d4e4B59220dA435A0bd6b5892B90fF50e1D8D4](http://hoodi.etherscan.io/address/0x42d4e4B59220dA435A0bd6b5892B90fF50e1D8D4) |
| &nbsp;  | rocketNodeManager                     | [0x1D174Fb276eD27451097B5A31D3Dc1f316491c0B](http://hoodi.etherscan.io/address/0x1D174Fb276eD27451097B5A31D3Dc1f316491c0B) |
| &nbsp;  | rocketNodeStaking                     | [0xBAcB8241421b83d8724CD57C0Df0056C13cFfdAa](http://hoodi.etherscan.io/address/0xBAcB8241421b83d8724CD57C0Df0056C13cFfdAa) |
| &nbsp;  | rocketRewardsPool                     | [0x4a625C617a44E60F74E3fe3bf6d6333b63766e91](http://hoodi.etherscan.io/address/0x4a625C617a44E60F74E3fe3bf6d6333b63766e91) |
| &nbsp;  | rocketSmoothingPool                   | [0xA347C391bc8f740CAbA37672157c8aAcD08Ac567](http://hoodi.etherscan.io/address/0xA347C391bc8f740CAbA37672157c8aAcD08Ac567) |
| &nbsp;  | rocketStorage                         | [0x594Fb75D3dc2DFa0150Ad03F99F97817747dd4E1](http://hoodi.etherscan.io/address/0x594Fb75D3dc2DFa0150Ad03F99F97817747dd4E1) |
| &nbsp;  | rocketTokenRETH                       | [0x7322c24752f79c05FFD1E2a6FCB97020C1C264F1](http://hoodi.etherscan.io/address/0x7322c24752f79c05FFD1E2a6FCB97020C1C264F1) |
| &nbsp;  | rocketTokenRPL                        | [0x1Cc9cF5586522c6F483E84A19c3C2B0B6d027bF0](http://hoodi.etherscan.io/address/0x1Cc9cF5586522c6F483E84A19c3C2B0B6d027bF0) |
| &nbsp;  | rocketUpgradeOneDotThree              | [0xa38f23783358e6Ce576441525bE0Ad6Dab5B0eF4](http://hoodi.etherscan.io/address/0xa38f23783358e6Ce576441525bE0Ad6Dab5B0eF4) |
| &nbsp;  | RocketUpgradeOneDotThreeHotfix        | [0xe068629fe7bf0242387f238Ab1AD66D6C3277f6F](http://hoodi.etherscan.io/address/0xe068629fe7bf0242387f238Ab1AD66D6C3277f6F) |
| &nbsp;  | RocketUpgradeOneDotThreeDotOne        | [0xC5bc3adEB85657EB82FB692Ef814760799d9Ab0A](http://hoodi.etherscan.io/address/0xC5bc3adEB85657EB82FB692Ef814760799d9Ab0A) |
| &nbsp;  | rocketVault                           | [0x67CdE7AF920682A29fcfea1A179ef0f30F48Df3e](http://hoodi.etherscan.io/address/0x67CdE7AF920682A29fcfea1A179ef0f30F48Df3e) |
| &nbsp;  | rocketNetworkSnapshots                | [0x0d8D8f8541B12A0e1194B7CC4b6D954b90AB82ec](http://hoodi.etherscan.io/address/0x0d8D8f8541B12A0e1194B7CC4b6D954b90AB82ec) |
| &nbsp;  | rocketNetworkVoting                   | [0x32778D6bf5b93B89177D328556EeeB35c09f472b](http://hoodi.etherscan.io/address/0x32778D6bf5b93B89177D328556EeeB35c09f472b) |
| &nbsp;  | rocketDAOProtocolSettingsProposals    | [0x7B8c48256CaF462670f84c7e849cab216922B8D3](http://hoodi.etherscan.io/address/0x7B8c48256CaF462670f84c7e849cab216922B8D3) |
| &nbsp;  | rocketDAOProtocolVerifier             | [0xf824e2d69dc7e7c073162C2bdE87dA4746d27a0f](http://hoodi.etherscan.io/address/0xf824e2d69dc7e7c073162C2bdE87dA4746d27a0f) |
| &nbsp;  | rocketDAOSecurity                     | [0x751826b107672360b764327631cC5764515fFC37](http://hoodi.etherscan.io/address/0x751826b107672360b764327631cC5764515fFC37) |
| &nbsp;  | rocketDAOSecurityActions              | [0x560656C8947564363497E9C78A8BDEff8d3EFF33](http://hoodi.etherscan.io/address/0x560656C8947564363497E9C78A8BDEff8d3EFF33) |
| &nbsp;  | rocketDAOSecurityProposals            | [0x89F478E6Cc24f052103628f36598D4C14Da3D287](http://hoodi.etherscan.io/address/0x89F478E6Cc24f052103628f36598D4C14Da3D287) |
| &nbsp;  | rocketDAOProtocolSettingsSecurity     | [0xE535fA45e12d748393C117C6D8EEBe1a7D124d95](http://hoodi.etherscan.io/address/0xE535fA45e12d748393C117C6D8EEBe1a7D124d95) |

<small>\* Testnet</small>

This list was updated 31/03/2025

The addresses can be queried on chain as shown in this [example](/overview/contracts-usage#interacting-with-rocket-pool).
