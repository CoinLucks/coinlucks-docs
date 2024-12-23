---
description: The following details are our core technical architecture selection.
---

# Technology

### Blockchain **>> opBNB Chain**

opBNB is a high-performance layer-2 solution within the BNB ecosystem, built using the OP Stack. Leveraging its block size of 100M, opBNB's gas fees remain stable and low cost, making it a great solution for widespread adoption across multiple digital environments. From gaming and decentralized exchanges to daily use and digital collectibles, opBNB caters to a diverse set of needs while delivering optimal performance.

### **Oracles >> Binance VRF**

Binance VRF (Verifiable Random Function) is a provably fair and verifiable random number generator (RNG) that enables smart contracts to access random values without compromising security or usability.

### **Storage >> IPFS/Pinata**

IPFS is a protocol and peer-to-peer network for storing and sharing data in a distributed file system.&#x20;

Pinata is an IPFS pin service provider, it makes file storage easy for everyone.

### **Subgraphs >> Goldsky & Sentio**

CoinLucks has written and open sourced a subgraph that provides, via a GraphQL query interface, useful aggregate calculations and event indexing for things like bets, draw, staking and user statistics data. The subgraph updates in real time as blocks are mined, and is reorg-aware. The subgraph underlies the primary CoinLucks.com interface, providing game data, activity history and more. The subgraph can be hosted by anyone but is also hosted and made publicly available by 3rd party providers, [Goldsky](https://goldsky.com/) and [Sentio](https://www.sentio.xyz/).
