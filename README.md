<p align="center">
<img height="200" src="/logo-serum.png">
</p>

# Awesome Serum [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![npm (scoped)](https://img.shields.io/npm/v/@project-serum/awesome-serum)](https://www.npmjs.com/package/@project-serum/awesom-serum)

A curated (unofficial) list of awesome things for people looking to buidl on Serum.
Please submit a pull request if you know any resources that might be helpful to other developers!

- [Blockchain](#blockchain)
  - [Solana](#solana)
  - [Serum](#serum)
- [Wallets](#wallets)
- [DEX Integration](#dex-integration)
- [Tutorials and Projects](#tutorials-and-projects)
- [Popular Token Contracts](#popular-token-contracts)

## Blockchain

### Solana

- [Solana Blockchain](https://github.com/solana-labs/solana)
- [Solana Program Library](https://github.com/solana-labs/solana-program-library)
- [Solana Web3 SDK](https://github.com/solana-labs/solana-web3.js)
- [Solana Explorer](https://github.com/solana-labs/solana/tree/master/explorer)
- [Solana Hello World](https://github.com/solana-labs/example-helloworld)
- [Solana Technical Documentation](https://docs.solana.com/)
- [Solana Discord](https://solana.com/discord)
- Solana Wormhole: bidirectional, trustless ERC-20 ⇄ SPL token bridge between Ethereum and Solana.
  - [Github repository](https://github.com/certusone/wormhole)
  - [Medium article](https://medium.com/certus-one/introducing-the-wormhole-bridge-24911b7335f7)
- [NFT example](https://spl.solana.com/token#example-create-a-non-fungible-token)
- [Run a Solana Validator Cluster](https://github.com/project-serum/validators)
- [Solana Go](https://github.com/dfuse-io/solana-go)

### Serum

- [RFC for node/staking code](https://github.com/project-serum/rfcs/blob/master/text/0001-registry.md) - Work in progress

## Wallets

- SPL Token Wallet:
  - [Github](https://github.com/serum-foundation/spl-token-wallet)
  - [Sollet.io](https://sollet.io/), powered by the source above
- [SOL Wallet Adapter](https://github.com/project-serum/sol-wallet-adapter), a library to allow Solana dApps to use third-party wallets to sign transactions.

## DEX Integration

A technical introduction to the Serum DEX can be found [here](https://docs.google.com/document/d/1isGJES4jzQutI0GtQGuqtrBUqeHxl_xJNXdtOv4SdII/edit?usp=sharing)

- [DEX source code](https://github.com/project-serum/serum-dex)
- [Serum.JS](https://github.com/project-serum/serum-js), client-side javascript resources to connect to the DEX
- [Serum DEX UI](https://github.com/project-serum/serum-dex-ui), an implementation of a UI for the Serum DEX
- Testnet deployment of prototype DEX
  - [DEX Program](https://explorer.solana.com/address/9JipvuvjcirpYf8mzYQtozXeYtQLWY67LaZCiANSMNgs)
  - [DEX Market](https://explorer.solana.com/address/2tJ2LVReFCZF81Ej4MAQHEr1kRSmk6QQ5XSnzjC9KJNj)
- Mainnet examples:
  - [DEX Program](https://explorer.solana.com/address/4ckmDgGdxQoPDLUkDT3vHgSAkzA3QRdNq5ywwY4sUSJn)
  - [DEX Market](https://explorer.solana.com/address/8AcVjMG2LTbpkjNoyq8RwysokqZunkjy3d5JDzxC6BJa)
- [PySerum](https://github.com/serum-community/pyserum): Python client library for interacting with the Project Serum DEX.

## Tutorials and Projects

- [Serum Academy](https://serum-academy.com)
- [Messaging App](https://github.com/kemargrant/soltalk) - Proof of Concept
- [AMM](https://github.com/solana-labs/solana-program-library/tree/master/token-swap) - Work-in-progress
- On-chain Pools:
  - [A general preview](https://docs.google.com/document/d/1lmMZRKkxMFOtGOEZOFEKYL7syqv-4QT87F0o55fc35Y/edit)
  - [Work in progress code](https://github.com/project-serum/serum-dex/tree/pool-wip/pool)
- [Bonfida](https://bonfida.com/):
  - [REST API](https://bonfida.com/blog/articles/serum-api) to get Serum market data
  - [GUI](https://github.com/dr497/serum-dex-ui)
  - [Wallet](https://github.com/dr497/spl-token-wallet)
- [Social Networks](https://github.com/project-serum/rfcs/pull/6)
  - [Messaging Backbone](https://github.com/project-serum/messaging-backbone-v1)
- [SPL Token Creator UI](https://www.spl-token-ui.com/)
- [Bonfida Token Minter](https://bonfida.com/mint)


## Projects in Production

Most of these projects are not open source. Use at your own risk.

### Web GUIs

- [Bonfida Serum DEX](https://bonfida.com/dex)
  - [Github](https://github.com/dr497/serum-dex-ui)
- [Cryptocurrencies.Ai DEX](https://dex.cryptocurrencies.ai/)
- [Serum Today](https://serum.today)
- [Serum Pro](https://serumpro.org)
- [Serum Folkvang.io](https://serum-mirror.folkvang.io/)
- [Project Serum DEX](https://dex.projectserum.com)
- [SerumStake DEX](https://dex.serumstakers.com)
- [Tech.Ed Training](https://serum.techedtraining.com/)
- [Santosha Exchange](https://exchange.santosha.digital)
- [Pangea DEX](https://pangeadex.com/)
- [SerumDex.Exchange](https://serumdex.exchange)
- [SolFlare DEX](https://dex.solflare.com)
- [Advance Finance DEX](https://advance.finance)
- [Viralic DEX](https://dex.viralic.io)
- [Illuminati Finance](http://illuminati.finance/serum)
- [Ourord DEX](https://dex.ourord.com)
- [BallsDeep DEX](https://serumdex.ballsdeep.me)
- [TradeOnSerum DEX](https://www.tradeonserum.com/)
- [YMAX DEX](https://ymax.finance/)
- [SRMSwap](https://srmswap.com/) （中文版）

### Mobile GUIs

- [Coin98](https://coin98.app)

#### NFT

- [Solible](https://solible.com)

### Web Wallets

- [Sollet.io](https://sollet.io)
  - [Github](https://github.com/project-serum/spl-token-wallet)
- [Bonfida Wallet](https://bonfida.com/wallet)
  - [Github](https://github.com/dr497/spl-token-wallet)
- [Math Wallet](https://mathwallet.org)
- [SolFlare](https://solflare.com)
  - [Guide](https://docs.solana.com/wallet-guide/ledger-live) on how to use a hardware Ledger with it.

### Mobile Wallets

- [Math Wallet](https://mathwallet.org)
- [Coin98](https://coin98.app)

### Yield Farms

- [Cryptocurrencies.ai](https://dex.cryptocurrencies.ai/rewards)
- [YMAX](https://ymax.finance/)

### AMM

- [SAMM](https://gitlab.com/OpinionatedGeek/samm)
  - [RFC](https://github.com/project-serum/rfcs/blob/master/text/0003-samm.md)
- [Swap](https://swap.projectserum.com/)
  - [code](https://github.com/project-serum/oyster-swap)

## Popular Token Contracts

- [Serum (SRM) SPL](https://explorer.solana.com/address/SRMuApVNdxXokk5GT7XD5cUUgXMBCoAz2LHeuAoKWRt)
- [Serum (SRM) ERC20](https://etherscan.io/token/0x476c5e26a75bd202a9683ffd34359c0cc15be0ff)
- [MegaSerum (MSRM) SPL](https://explorer.solana.com/address/MSRMcoVyrFxnSgo5uXwone5SKcGhT1KEJMFEkMEWf9L)
- [MegaSerum (MSRM) ERC20](https://etherscan.io/token/0x1320c8c64b9f2eAa851F70702e6C9FC1EE4E8Ce4)
