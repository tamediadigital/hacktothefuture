---
layout: hack
title: Payment on Delivery - Connecting Swiss Post to Cardano Smart Contracts
---

[Cardano](https://cardano.org/) is a blockchain platform which recently added [smart contracts](https://en.wikipedia.org/wiki/Smart_contract). This allows funds to be transferred programmatically based on some event.

### Goal of Hack

Build a proof-of-concept [escrow](https://en.wikipedia.org/wiki/Escrow) mechanism so that if someone buys a product from Ricardo or tutti.ch, the payment is placed in escrow using a smart contract then released when the Swiss Post [reports the product was delivered](https://www.post.ch/en/business-solutions/digital-commerce/track-consignments-web-service).

In reality it will be difficult to accomplish this in 1 day and will probably fail, but the secondary goal is understanding the various technologies involved.

### Who's Leading this Hack

Harry Fuecks - harry.fuecks (TX Group workspace)

### Things to know about

- Using the [Cardano testnet](https://developers.cardano.org/docs/get-started/testnets-and-devnets/)
-- Need to figure out the basics of programmatically sending / receiving money (Ada - the currency that runs on the Cardano platform)
- How [Cardano Smart Contacts](https://developers.cardano.org/docs/smart-contracts/) work
- How to create an [Oracle Pool](https://cardanians-io.medium.com/oracles-in-the-cardano-ecosystem-3cb4a71e9509) that will report on the state of the [Swiss Post tracking webservice](https://www.post.ch/en/business-solutions/digital-commerce/track-consignments-web-service)


